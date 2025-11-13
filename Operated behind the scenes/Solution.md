# Operated Behind the Scenes — solution

---

## Steps

### 1. Start with the crypto address
We begin with the provided Ethereum address: `0x7bF443423C4a6171Be6291eD1CD33C9A5129929C`


Checking **Etherscan** reveals nothing useful, so we pivot to **Chain-Abuse**, given the ransomware-themed context.

Chain-Abuse **finds a match** for malicious activity, referencing a domain:

- `www.ecwmoney.fr`

This suggests a ransomware dashboard.

---

### 2. Investigate the ransomware dashboard
Visiting **ecwmoney.fr**, we find a classic ransomware “panel”:

- List of compromised companies
- Negotiation statuses
- Leak statuses

We proceed to gather metadata on the domain.

---

### 3. Run domain enumeration
Using **web-check.xyz** on `ecwmoney.fr` reveals:

- A `.well-known/security.txt` file  
- Inside it: an attacker contact email, `7331uhluhtc@gmail.com`


This is our next pivot point.

---

### 4. Lookup the attacker’s email
We search the email with **Epieos** and retrieve:

- A Google profile ID
- Associated links, including a **Google Calendar**: `https://calendar.google.com/calendar/u/0/embed?src=7331uhluhtc@gmail.com`


---

### 5. Inspect the Google Calendar
The attacker’s calendar contains a **public event**.  
From it, we extract:

- **Date:** 04/11  
- Year inferred from context: **2025**

The event also contains a **photo**.

---

### 6. Identify the location via the event photo
Reverse image searching the event photo yields:

- Match with **Atlas Studios, Ouarzazate (Morocco)**

Thus we obtain the city required for the flag.

---

### 7. Determine the time
Exif metadata → **no timestamp**.

We analyze the image:

- Long shadows
- Sun is low → sunrise or sunset
- In early November, Ouarzazate sunrise is ~7 AM, sunset is ~6 PM
- Light corresponds to **sunset**

We test both possible times → **18:00** works.

---

## Result
`ECW{Ouarzazate:04:11:2025:18}`


