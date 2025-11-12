# Jobstacle_II — solution

---

## Part 1 — IP address

**Bot intro:** notebook with four dated verses; route: hideout near **Ibn Khaldoun mosque** → **north-west** to departmental archives; 4 “clean” pharmacies; two coordinate pairs:
- Hideout area: **48.12939945601638, -1.6943130170587877**
- Archives: **48.093306482270535, -1.6520208744113876**

Focus search on pharmacies **between those points**. Each verse yields one number:

1) **Aug 2023** — “tryptich of arrows… number on top”  
   Street View (2023) near a pharmacy shows **three arrows** with **125** above → **125**.

2) **Feb 2025** — “old bourgeois boulevard… watch the temperature”  
   **Pharmacie Léon Bourgeois** (Bd Léon Bourgeois), Street View **Feb 2025**, sign shows **10 °C** → **10**.

3) **[erased] 2023** — tech repair shop whose **name puts many at ease**  
   Repair shop **Mobile35** (intended: **PC35**) covered in **2023** → **35**.

4) **Mar 2022** — media shop with **yellow storefront**, “truth lies somewhere inside”  
   **O’CD** storefront (Street View **Mar 2022**) shows **2** inside → **2**.

**IP assembled:** `125.10.35.2`

---

## Part 2 — Person of Interest

**Bot hint:** contact tied to **Julien Martinano**; maybe **Lycée Saint Martin (Rennes)**; sparse Instagram.

1) Find **Lycée Saint Martin Rennes** → school IG.  
   In **tagged** posts, locate account **@theskyisfalling48** referencing **J Martinan0**.

2) On the relevant post:  
   - **QR code** → when decoded at data level reveals `ecw-Victoire`.  
   - **Comment** includes Base64: `c3RlYW0taWQ6Lzc2NTYxMTk5ODYwODIwMTUyLw==` → `steam-id:/76561199860820152/`.

3) Lookup **SteamID 76561199860820152** → user `PepitoChrysali`.  
   **Previous names** include `ecw-Lanctot` → surname **Lanctot**.

**Full name:** **Victoire Lanctot**

---

## Result
`ECW{125.10.35.2_Victoire_Lanctot}`