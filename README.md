[README.md](https://github.com/user-attachments/files/34612741/README.md)
# 🚀 iebLabs Micro-Tools Collection

A curated collection of fast, privacy-friendly, zero-backend micro web applications designed to solve everyday legal, financial, and organizational problems in seconds.

Built with clean HTML5, Tailwind CSS, and vanilla JavaScript. No trackers, no bloatware, mobile-first.

**Author:** [@iebLabs](https://github.com/iebLabs)

---

## 🛠️ All Tools at a Glance

| # | Tool | Category | What it solves |
|---|------|----------|----------------|
| 01 | **[AbfindungsCheck](./01-abfindungscheck)** | Employment Law | Severance pay calculator based on § 1a KSchG |
| 02 | **[SpritKostenTeiler](./02-spritkostenteiler)** | Everyday Finance | Fair fuel cost splitting for road trips & carpooling |
| 03 | **[KitaPlatzHelfer](./03-kitaplatzhelfer)** | Family Law | Legal appeal letter for denied childcare (§ 24 SGB VIII) |
| 04 | **[ElternOpti](./elterngeldopti)** | Parental Benefits | Parental allowance calculator (Basiselterngeld & ElterngeldPlus) |
| 05 | **[TierarztKostenCheck](./tierarztkostencheck)** | Pet Owners | Vet cost estimator based on German GOT fee schedule |
| 06 | **[BioCraft](./biocraft)** | Social Media | Viral Instagram, TikTok & LinkedIn bio generator |
| 07 | **[ErbeRechner](./erberechner)** | Inheritance Law | Legal inheritance share & forced heirship calculator |
| 08 | **[StromFresserFinder](./stromfresserfinder)** | Energy & Savings | Annual electricity cost calculator per household appliance |
| 09 | **[UrlaubsMaximierer](./urlaubsmaximierer)** | Productivity | Bridge day planner to double vacation days (by German state) |
| 10 | **[HandwerkerSteuer](./handwerkersteuer)** | Tax Refund | Craftsman invoice tax deduction calculator (§ 35a EStG) |

---

## 📖 Tool Details

### 1. AbfindungsCheck
- **Problem:** You received a job termination and need to know your estimated severance payout.
- **Key Features:**
  - Standard & custom settlement factor calculation (0.25x – 1.5x)
  - Critical 3-week lawsuit deadline warning
  - Tax optimization info (Fünftelregelung § 34 EStG)
  - Attorney consultation lead flow

### 2. SpritKostenTeiler
- **Problem:** Splitting fuel costs fairly after a road trip, festival, or daily commute.
- **Key Features:**
  - Fuel consumption + price + toll/parking cost calculation
  - Optional vehicle wear & tear allowance (+0.05 €/km)
  - 1-click WhatsApp group settlement message generator
  - Integrated `PayPal.me` payment link generation

### 3. KitaPlatzHelfer
- **Problem:** Your child was denied a public daycare spot despite the legal right (§ 24 SGB VIII).
- **Key Features:**
  - Formal objection letter with strict 14-day legal deadline
  - Loss-of-earnings and private nanny reimbursement references (BGH ruling)
  - Clean print & clipboard export

### 4. ElternOpti
- **Problem:** Calculating parental leave benefits and optimizing partner months.
- **Key Features:**
  - Basiselterngeld vs. ElterngeldPlus comparison
  - Sibling bonus & multiple birth surcharge
  - Tax class switching trick explanation (up to 3,000 € more)

### 5. TierarztKostenCheck
- **Problem:** Estimating vet bills under the new German veterinary fee schedule (GOT).
- **Key Features:**
  - 1x to 4x fee factor selector (regular to emergency)
  - Emergency surcharge toggle (+ 59.50 € legal base fee)
  - Common treatments for dogs, cats, and small animals
  - Pet health insurance affiliate integration

### 6. BioCraft
- **Problem:** Writing a compelling, converting social media bio from scratch is hard.
- **Key Features:**
  - 6 niche presets (Fitness, Business, Beauty, Tech, Travel, Creator)
  - 4 optimized bio variants with emojis & CTAs per generation
  - One-click copy to clipboard
  - Link-in-bio tool recommendation

### 7. ErbeRechner
- **Problem:** Understanding inheritance distribution and forced heirship after a death.
- **Key Features:**
  - Statutory inheritance vs. forced heirship (Pflichtteil) toggle
  - Spousal share under community of gains vs. separation of property
  - Inheritance tax exemption table (500k spouse / 400k children / 200k grandchildren)
  - Notary & estate attorney lead integration

### 8. StromFresserFinder
- **Problem:** Identifying which old household appliance is burning the most electricity (and money).
- **Key Features:**
  - Preset wattage templates (fridge, gaming PC, TV, space heater, standby drain)
  - Custom watt + hours input with real-time yearly cost output
  - Electricity price per kWh adjustment
  - Energy provider switching affiliate (Check24)

### 9. UrlaubsMaximierer
- **Problem:** Maximizing time off by strategically placing vacation days around public holidays.
- **Key Features:**
  - 2026 bridge day calendar with optimal vacation slots
  - State-specific holiday display (Niedersachsen, Bayern, NRW, Berlin, etc.)
  - Shows vacation day input vs. total free days gained
  - Travel booking affiliate (Booking.com)

### 10. HandwerkerSteuer
- **Problem:** Most homeowners don't know they can claim 20% of craftsman labor costs back from the tax office.
- **Key Features:**
  - § 35a Abs. 3 EStG calculator (max 1,200 €/year tax credit)
  - Previously claimed amount deduction to track annual limit (6,000 € labor cap)
  - Bank transfer requirement warning (cash payments are rejected)
  - Tax software affiliate integration (Taxfix, WISO)

---

## 🚀 Deployment

All tools are standalone single-page applications with zero dependencies beyond CDN-loaded Tailwind CSS and FontAwesome. Deploy any subfolder to:

- **Netlify:** Drag & drop the folder at [app.netlify.com/drop](https://app.netlify.com/drop)
- **Vercel:** Import the GitHub repo and set the root directory to any subfolder
- **GitHub Pages:** Enable Pages in repository settings

---

## 💰 Monetization

Each tool includes built-in placeholders and integrations for:

1. **Google AdSense** – Banner slots (top & bottom)
2. **Affiliate Links** – Category-specific partner programs (Check24, Taxfix, Booking.com, etc.)
3. **Freemium Gating** – Premium PDF exports or unlimited usage
4. **Lead Generation** – Email capture and professional service referrals

---

## 📄 License

MIT License. Built by **iebLabs**.
