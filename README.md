# 🚬 Anold Vapes (AV) — Premium Vape Store

![Status](https://img.shields.io/badge/Status-Live-success)
![Made in Botswana](https://img.shields.io/badge/Made%20in-Botswana%20🇧🇼-blue)
![18+](https://img.shields.io/badge/18%2B-Restricted-red)

A modern, dark-themed e-commerce website for **Anold Vapes** — Gaborone's premium vape destination.

---

## ✨ Features

- 🔞 **Age verification gate** — 18+ check on first visit (localStorage)
- 🎥 **Live video hero** — cinematic background of vape usage
- 🛒 **Full working cart** — persistent via localStorage
- 💨 **48 products** across 9 categories
- 🎯 **Advanced filters** — category, brand, nicotine, price range, in-stock
- 🔍 **Sort options** — latest, price low→high, price high→low, A–Z
- ⭐ **Wishlist** — save products for later
- 📄 **Product detail pages** — full specs, descriptions, related items
- 📱 **Mobile-first** — native-app feel with slide-out menu and filters
- 📲 **WhatsApp checkout** — orders sent as formatted messages
- 🎨 **Dropdown menus** — shop and brands sub-navigation
- ⚠️ **Legal warnings** — nicotine addiction warning in footer
- 🍞 **Toast notifications** — non-intrusive feedback

---

## 📁 File Structure

---

## 🎨 Design

| Element | Choice |
|---------|--------|
| **Base** | Matte Black `#0A0A0B` |
| **Primary accent** | Electric Lime `#C4F000` |
| **Secondary accent** | Vapor Purple `#8B5CF6` |
| **Display font** | Anton |
| **Body font** | Inter |

Premium vape boutique aesthetic — not corner shop.

---

## 🚀 Deploy to GitHub Pages

1. Create repo: `anold-vapes`
2. Upload all 7 files to root
3. **Settings → Pages → main branch → Save**
4. Live at `https://YOUR-USERNAME.github.io/anold-vapes/`

---

## 🛠️ Customisation

### Change WhatsApp number
Search all files for `26771234567` and replace.

### Add or edit products
Edit the `products` array in `main.js`. Fields:
- `id`, `name`, `brand`, `category`, `price`, `emoji`, `puffs`, `flavour`, `nicotine`, `badge`, `inStock`, `description`

### Change the hero video
In `index.html`, replace the `<source>` URLs in `<video class="hero-video">`.

---

## ⚠️ Legal Notice

Vaping products are regulated in Botswana under the **Tobacco Control Act 2021**. Before launch:
- Ensure valid trading licence
- Age verification on-site and in-person
- Health warnings displayed

This demo includes an age gate and warnings but does not guarantee regulatory compliance.

---

## 📄 License

MIT License.

---

### ❤️ Built in Gaborone, Botswana 🇧🇼
