# SOSS — solution

Pivot from the movie-friendly handle to **Letterboxd → Instagram → GitHub**, grab a photo, read its EXIF GPS, convert to the required format, submit.

---

## Steps

1. **Start from the clue**
   - The spy is a movie fan; check film-centric socials.
   - Go to **Letterboxd** and try the handle:
     - https://letterboxd.com/ecwthief

2. **Extract the pivot**
   - In a review of *OSS 117: Cairo, Nest of Spies (2006)* (★ ★ ★ ★ ★ – Watched **20 Jun 2025**), the text says:
     > *“…If you want to follow me, just find me: **labath_d_hubert** …”*
   - New username to pivot: **`labath_d_hubert`**.

3. **Fan-out on socials**
   - Instagram: find **`labath_d_hubert`** (not directly solvable from there).
   - GitHub: find **`labath_d_hubert`** with a repo **`meet_me_using_the_matrix`**.
     - Repo contains a Python script (visual “matrix” effect) **and a picture**.

4. **Pull the artifact & read EXIF**
   - Download the **picture** from the repo.
   - Run EXIF:
     ```bash
     exiftool photo.jpg
     ```
   - **Bingo**: GPS tags present (latitude & longitude).

5. **Convert & format**
   - Convert the GPS to decimal and format **exactly** as required:
     ```
     ECW{<latitude>° <N/S> <longitude>° <E/W>}
     ```
   - Use the **comma** separator and **6 decimals**.

---

## Result
`ECW{29,844117° N 6,237172° W}`