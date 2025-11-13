# Larry's Enigmas (OSINT) — ECW CTF 2025

**Difficulty:** Medium  
**Points:** 191  
**Solves:** 133  
**Category:** OSINT  
**Author:** ASTEK

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
``` 
My friend,

I have to keep my location secret.
Hence, I won't give you my location in clear.
Cypher algorythms could be cracked by the quantum or something 
(I fear because I do not understand fully)

I am sure you, out of everybody, will be able to understand me.

I currently live with the dog.

We have a lot to discuss in person.
Sincerely yours,
See you soon,
Larry
```
![alt text](provided_files/LarrysEnigma.png)
