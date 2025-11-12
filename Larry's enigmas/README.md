# PetBeacon (OSINT) — ECW CTF 2025

> **Difficulty:** Medium  
> **Category:** OSINT  
> **Points:** 191 
> **Solves:** 133 
> **Author:** ASTEK  
---

## Challenge Prompt
Larry wants to meet up, but he shares his position in the most inconvenient way: this time he’s using a **pet biochip** as a beacon.  
Your job is to recover Larry’s approximate location from the chip data and then **find the nearest bus stop** to that position.

---

## Flag Format
`ECW{City_n°bus_BusStopName}`

**Example:** `ECW{Tbilisi_316_FreedomSquare}`

- `City` → city name (capitalize normally, spaces removed or replaced by camel/pascal case if needed).  
- `n°bus` → **route number** (or route code) of the nearest bus serving the closest stop to Larry’s position.  
- `BusStopName` → the **official stop name** as it appears on the local transit source (remove problematic punctuation if required by the platform).

---

## Provided Files
_No explicit files are listed here._  
Expect artifacts such as:
- A **photo/screenshot** of a reader (e.g., Flipper Zero) showing **ISO FDX-B** tag data: country code + 15-digit ID.
- A note or breadcrumb pointing to an **official registry** (e.g., by country).
