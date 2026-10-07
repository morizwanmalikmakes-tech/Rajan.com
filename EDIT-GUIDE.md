# ✏️ RAJAN COMMUNICATION — WEBSITE EDIT GUIDE (PREMIUM EDITION)

> **Design:** Aurora Premium — animated gradient glow, bento grid, glassmorphism,
> serif accent typography (Instrument Serif), smooth scroll reveals, scroll-progress bar,
> hero parallax. Fonts: Plus Jakarta Sans (headings) + Inter (body) + Instrument Serif (accents).

## 1. SABSE ZAROORI — Phone / WhatsApp / Address
`index.html` file kholo (Notepad ya kisi bhi editor me) → neeche `EDIT_CONFIG` dhoondo
(shortcut: Ctrl+F → `EDIT_CONFIG`). Bas yahan 4 cheezein badlo:

```js
const EDIT_CONFIG = {
  phone:        "+91 98XXXXXXXX",     // asli number (0 ya +91 ke saath)
  whatsapp:     "9198XXXXXXXX",       // country code ke saath, bina + ke
  directionsUrl:"https://maps.app.goo.gl/XXXX",   // Google Maps link (Share → Copy link)
  mapsSearch:   "Rajan Communication Kundli Haryana"
};
```

Save karo — poore website pe (top bar, hero, buttons, footer, mobile bar) sab jagah
number apne aap badal jayega. **25+ jagah** manually badalne ki zaroorat nahi.

## 2. Baaki cheezein (jahan "[...]" dikhe)
File me Ctrl+F karke `[` search karo. Jo bhi square bracket me hai, wo placeholder hai:
- `[BUSINESS HOURS]` → jaise "Mon–Sun 9:00 AM – 9:00 PM"
- `[PHONE NUMBER]` / `[WHATSAPP NUMBER]` → asli numbers
- `[Exact street address — owner se lena hai]` → pura pata
- `[Product photo add karni hai]` → product ki asli photo
- `[Price on request]` → asli price
- Offer cards → asli offer
- Reviews → asli customer review (jhoothi review kabhi nahi)

## 3. Photos kaise badalni hai
`assets/` folder me 5 photos hain:
| File | Kahan dikhti hai |
|---|---|
| `hero-store.jpg` | Hero (top) + gallery |
| `about-store.jpg` | About section + gallery |
| `g-covers.jpg` | Gallery — covers/glass |
| `g-repair.jpg` | Gallery — computer service |
| `g-earbuds.jpg` | Gallery — earbuds/powerbanks |

**Nayi photo lagane ka tarika:** apni photo ko wahi naam de do (jaise `hero-store.jpg`)
aur `assets` folder me replace kar do. Website apne aap nayi photo dikhayegi.
👉 Photo 1500px wide, JPEG (quality 75-80) rakho — fast load hoga.

## 4. Google Maps lagana (jab pura address mile)
1. Google Maps kholo → "Rajan Communication Kundli" search karo
2. Share → "Embed a map" → code copy karo (jo `<iframe ...>` se shuru hota hai)
3. `index.html` me `<!--` aur `-->` ke beech wala iframe comment plain karo aur apna iframe paste karo
4. Uske just upar wala `<div class="pin">...</div>` block delete kar do

## 5. Website live karne ke liye (hosting)
- **Domain:** jaise rajancommunication.in (₹700-900/saal)
- **Hosting:** free options bhi hain (Netlify / GitHub Pages / Cloudflare Pages) — files upload karo, URL mil jayega
- Ya normal hosting (Hostinger ₹1,500-2,500/saal) — cPanel me `public_html` me daal do

## 6. SEO ka kya hua
- Title, meta description, keywords — sab already bhare hain (Kundli, Sonipat wale)
- Open Graph tags — WhatsApp/Facebook pe link bhejne pe photo + title aayega
- **LocalBusiness schema** (ElectronicsStore) — Google me business info dikhti hai
- Har image pe alt text hai
- **Ek kaam aur karna hai:** Google Business Profile banwa lo (free) — Google Maps + search me dikhoge. Usme website ka link daal dena. (Ye main bana ke de sakta hoon)

## 7. Kya-kya jaan-boojh kar NAHI lagaya
Jhooth nahi likha gaya — koi banaya hua review nahi, koi fake price nahi, koi fake
discount nahi, koi "10 saal ka anubhav" jaisa claim nahi. Jahan asli info nahi thi,
wahan saaf `[placeholder]` hai. Owner jab deta hai, tab bharna hai.

---
**Banaya gaya:** 7 Oct 2026 | Single-file website + 5 optimised images | Total size ~700 KB
