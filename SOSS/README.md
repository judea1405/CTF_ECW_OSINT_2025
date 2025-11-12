# Who’s That Spy? (OSINT) — ECW CTF 2025

> **Difficulty:** Medium  
> **Points:** 289  
> **Solves:** 110  
> **Category:** OSINT  
> **Author:** DGA

---

## Challenge Prompt
We have obtained more information about this spy. He is a **movie fan** and his username is: **`ecwthief`**.  
Pivot from this handle using only open-source information to determine the spy’s **exact coordinates**.

---

## Flag Format
- Use a **comma** as the thousands separator in the decimals, include the **degree symbol (°)** and the **cardinal letters**.
- Keep **exact precision** (6 decimal places).

---

## Provided Files
_No additional files are provided for this challenge._  
You must rely on **open-source intelligence (OSINT)** using the username and context above.

---

## Rules
- Only use **publicly available** information (no contacting targets, no paid databases, no brute force).
- Respect website **ToS** and **rate limits**.
- Submit the flag in the **exact** format shown.

---

## What You’re Likely Dealing With
- A handle (**`ecwthief`**) that may be reused across platforms.  
- Film-centric profiles (watchlists, reviews, lists, event check-ins) that can leak **places and times**.  
- Posts or images that may reveal **venue names** or **landmarks** → convert to precise **GPS coordinates**.

---

## Hints (Optional — Progressive)
1. Start with **username pivoting** on major platforms and movie sites (search engines, social media, Letterboxd/IMDb-alikes).  
2. Look for **bio links**, pinned posts, or **custom URLs** chaining to smaller platforms.  
3. Movie fans often share **theaters, festivals, screenings**—these can map to **exact lat/long**.  
4. Cross-check suspected locations with **official venue pages** and **map services** to obtain coordinates to 6 decimals.  
5. Verify if any posted photo captions, EXIF (when public), or event pages expose precise coordinates.

---

## Submission
- Submit via the platform in the exact format: `ECW{<latitude> <N/S> <longitude> <E/W>}`
- Example (format only): `ECW{12,789456° N 9,895623° W}`

