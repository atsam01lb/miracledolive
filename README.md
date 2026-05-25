# Miracle d'Olive 🫒☀️

A light, summery single-page website for **Miracle d'Olive** — 100% organic summer skincare.
Customers browse products, add them to a basket, and check out directly via **WhatsApp**.

## ✨ Features
- Fully responsive, mobile-friendly summer design
- Shopping basket with quantity controls (no backend needed)
- One-tap **WhatsApp checkout** — the order summary is pre-filled into a message
- "Coming soon" badges for products not yet launched
- Instagram + WhatsApp contact links
- Pure HTML/CSS/JS — no build step, no dependencies

## 📦 Products
| Product | Status |
|---|---|
| Organic Sun Tan Oil | Available |
| Organic After Sun | Available |
| Organic Luffa Soap | Coming soon |
| Organic Facial Soap | Coming soon |

## 🛠 How to edit

### Prices & products
Open `index.html` and find the `PRODUCTS` array near the top of the `<script>` section.
Each product has a `price`, `vol` (volume), `desc`, and `available` flag (set `true` to make it buyable).

```js
{
  id:"suntan-oil",
  name:"Organic Sun Tan Oil",
  price:18,          // <-- change price here
  vol:"100 ml",
  available:true     // <-- false = "Coming Soon"
}
```

> ⚠️ Prices are placeholders ($18 / $9). Update them to the real prices before going live.

### WhatsApp number
At the top of the `<script>` section:
```js
const WHATSAPP_NUMBER = "96179409960"; // 961 = Lebanon, then the number without the leading 0
```

### Currency
```js
const CURRENCY = "$";
```

## 🚀 Deploy on GitHub Pages
1. Create a new repository (e.g. `miracle-dolive`) and push these files.
2. Go to **Settings → Pages**.
3. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save. Your site will be live at `https://<username>.github.io/miracle-dolive/` in a minute.

## 📁 Structure
```
miracle-site/
├── index.html
├── README.md
└── assets/
    ├── logo.svg              (full turquoise logo)
    ├── logo-white.svg        (white logo for footer)
    ├── palms-white.svg       (palm motif, white)
    └── palms-turquoise.svg   (palm motif, turquoise)
```

## 📱 Contact
- WhatsApp: **79 409 960**
- Instagram: [@miracledolivelb](https://instagram.com/miracledolivelb)

---
Made with 🫒 in Lebanon.
