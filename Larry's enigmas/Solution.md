# PetBeacon — solution

## TL;DR
Chip ID `123412341234123` → lookup on **PetMaxx** → 3 registry matches (Ukraine, Germany, Netherlands).  
Larry’s message says *“I currently live with the dog”* → follow the **Dutch (dog)** record.  
Dutch registry gives address **Cypresbaan 43, Capelle aan den IJssel, 2908LT, NL** → city **Rotterdam area**.  
Nearest bus stop: **Vlierbaan**, served by **bus 190**.  
Flag: `ECW{Rotterdam_190_Vlierbaan}`

---

## Steps

1. **Extract the chip ID**
   - From the image: `ID: 123-412341234123` → usable ID = **123412341234123**.

2. **Search on PetMaxx**
   - Visit [PetMaxx](https://www.petmaxx.com) to perform an **international microchip search**.
   - The ID yields **three results**:
     - Ukraine (cat)  
     - Germany (cat)  
     - Netherlands (dog)

3. **Follow the correct lead**
   - Larry’s message says: *“I currently live with the dog.”*
   - Therefore, choose the **Dutch (dog)** registry entry.

4. **Retrieve the address**
   - The Dutch registry lists:  
     **Cypresbaan 43, Capelle aan den IJssel, 2908LT, Netherlands**

5. **Identify the city**
   - Capelle aan den IJssel is part of the **Rotterdam metropolitan area** → `City = Rotterdam`.

6. **Find the nearest bus stop**
   - Check public transport data for the address.
   - Closest stop: **Vlierbaan**, served by **bus 190**.

7. **Assemble the flag**
## Result
ECW{Rotterdam_190_Vlierbaan}