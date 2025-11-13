# DroneGuesser_II (OSINT) — ECW CTF 2025

> **Difficulty:** Medium  
> **Points:** 100  
> **Category:** OSINT  
> **Author:** ASTEK

---

## Challenge Prompt
Your friend crashed his FPV drone and **lost a motor** a while ago. Let’s offer him a replacement so he can get back to making that mesmerizing footage.

You are given **his profile picture** (attached).  
From this, **identify the exact motor reference** and extract the **testing data** needed for the flag.

> **Find:** the **reference** and the **official technical specs** of the lost motor.  
> Use values from the **testing data** (manufacturer/official bench or the reference test table linked on the product page).

---

## Flag Format
`ECW{MOTORType_MaxThrust_MaxThrustRPM}`

- `MOTORType` → the **exact motor reference** (e.g., Brand_Model_StatorKV style; use the manufacturer’s naming).  
- `MaxThrust` → **maximum thrust** value from the testing table (use the **decimal precision** shown there).  
- `MaxThrustRPM` → the **RPM at which that max thrust occurs** (from the same table).

**Accepted formats (due to varying decimals in sources):**
`(old): ECW{_**._}
(true): ECW{****_._*****}`

Both will be accepted.

---

## Provided Files
![alt text](provided_files/NotLarry.png)