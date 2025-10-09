# MiniSnickarna — Bygg, lek och lär ✨🔨

[![Static Site](https://img.shields.io/badge/site-static-green)](#)
[![Built with Tailwind](https://img.shields.io/badge/tailwind-css-blue)](#)
[![GitHub Pages](https://img.shields.io/badge/deploy-GitHub%20Pages-black)](#)

**MiniSnickarna** är en enkel, barnvänlig, statisk hemsida för en prenumerationsbox där barn bygger på riktigt.  
Fokus: trygghet, kreativitet och stolthet över att skapa med händerna.

> 🌍 **Live**: https://pierreslag.github.io/minisnickarna/

---

## 🎯 Features
- Responsiv design (mobil först), mörkt/ljust läge  
- Klara sektioner: **Hero**, **Så funkar det**, **Boxar**, **Priser**, **CTA**, **Footer**  
- Inga build-steg: **ren HTML** + **Tailwind via CDN**  
- Snabba “ikonbilder” med emoji (noll externa JS-bibliotek)  
- Lätt att byta texter, färger, bilder och priser  

---

## 🗂 Struktur
├─ index.html # Hela sidan (statisk)
├─ README.md # Den här filen
└─ assets/
└─ logo.svg # Enkel SVG-logga

---

## 🚀 Publicering (GitHub Pages)
1. **Commit + push** allt till `main` i det här repot  
2. Gå till **Settings ▸ Pages**  
   - **Source:** Deploy from a branch  
   - **Branch:** `main`  
   - **Folder:** `/ (root)`  
3. Klicka **Save**  
4. Vänta ~1 minut och öppna:  
   **https://pierreslag.github.io/minisnickarna/**  

> 💡 Tips: Om sidan inte uppdateras direkt – gör en liten ändring (t.ex. i README), commit + push igen.

---

## 🛠 Lokal utveckling (valfritt)
Ingen build behövs. Öppna bara `index.html` i din webbläsare  
(eller kör via VS Code “Live Server” för auto-reload).

---

## ✏️ Anpassa
- **Logga:** byt ut `assets/logo.svg` mot din egen  
- **Texter/priser:** ändra direkt i `index.html`  
- **Bilder:** ersätt emoji-ikoner med foton eller illustrationer  

---

## ➕ Nästa steg (idéer)
- Swish-knapp (mock) + kontaktformulär som sparar i `localStorage`  
- QR-kod till videoguide för varje box  
- Enkel kundvagn/summering (fortfarande statiskt)  
- Eget domännamn via `CNAME` (t.ex. `minisnickarna.se`)  

---

## 👷‍♀️ Team & vision
MiniSnickarna är ett projekt i startfasen med fokus på lekfullt lärande och hållbar design.  
Målet är att skapa en plattform där barn kan **bygga, måla och förstå** världen runt sig – ett litet steg i taget.  

---

## 📜 Licens
© MiniSnickarna. All rights reserved.
