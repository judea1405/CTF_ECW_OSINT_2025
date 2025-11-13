# Operate Behind the Scenes — ECW CTF 2025

> **Difficulty:** Hard  
> **Points:** 434  
> **Solves:** 62  
> **Category:** OSINT / Crypto  
> **Author:** DGA

---

## Challenge Prompt
> *“I think he's spotted us: he's encrypted our PC and is demanding a transfer to the following address:”*  

Ethereum address: `0x7bF443423C4a6171Be6291eD1CD33C9A5129929C`


Your objective is to determine:

- **The city** where he is located  
- **The day, month, year** corresponding to his activity  
- **The hour** (00–23)  

Follow all available breadcrumbs tied to this wallet and any associated accounts, services, or leaked data.

---

## Flag Format
`ECW{City:DD:MM:YYYY:HH}`


**Examples (format only):**  
- `ECW{Paris:01:01:2025:13}`  
- `ECW{Tokyo:31:12:2024:22}`  

City names should be written without spaces.

---

## Provided Information
- One **Ethereum address** used for ransom demands.  
- No other direct files — the rest must be uncovered through open-source investigation.




