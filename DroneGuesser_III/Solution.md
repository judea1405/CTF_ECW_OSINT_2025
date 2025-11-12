# DroneGuesser_III — solution

---

## Steps

1. **Find the socials**
   - Reverse image search the profile picture → locate the **YouTube channel** (`rev`, `channel`).
   - Channel content is FPV-focused; identify video: **「我的馬達咧？I lost my motor!!」** (`vid1`).

2. **Identify the crash spot in the video**
   - Crash occurs around **5:48** among a group of trees (`crash`), close-up of the specific tree (`zoom`).

3. **Geo-pivot from unique landmarks**
   - Background includes **yellow pillars** along a coastline (`pillars`).
   - Reverse image search on the pillars (`rev2`) → a **touring website** of the area (`tour`).

4. **Narrow to the district & park**
   - Landmarks are in **Qijin District, Taiwan** (`Qijin`).
   - Satellite scan of the small area → row of pillars at **Qijin Windmill Park** (`park`).
   - Match the **tree cluster** seen in the footage, nearest to the windmill park (`trees`).

5. **Pin the exact tree & round**
   - Dropped a pin at the crash tree: **22.588324, 120.284797**.
   - Round to **3 decimals** (standard rounding): **22.588, 120.285**.

---

## Result
`ECW{22.588, 120.285}`