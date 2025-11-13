# WhosDatCat? — solution

## Evidence (from image 1)
- Device: Flipper Zero
- Type: **ISO FDX-B**
- ID shown: **250-269602787277**
- Country Code: **250** (France)

## Reasoning
- ISO FDX-B → animal microchip standard (15-digit ID).
- Country code **250** = France → lookup on the French registry **I-CAD**.
- Searches are done with the 15 digits only (without the country prefix).

## Steps to reproduce
1. Open: https://www.i-cad.fr/verifier-animal-chien-chat-enregistrement-fichiers-officiels  
2. Search for **269602787277**.  
3. The result shows the species (**cat**) and the animal’s **given name**.

## Flag
`ECW{Arthur}`
