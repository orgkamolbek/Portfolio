# 🌐 Master Portfolio: Responsive Personal Showcase Hub

Dasturchining shaxsiy brendi, ko'nikmalari, amalga oshirgan loyihalari va aloqa kanallarini zamonaviy interfeys orqali taqdim etuvchi professional portfolio veb-sayti. Loyiha to'liq moslashuvchan (Responsive), animatsiyalarga boy va foydalanuvchi tajribasiga (UX) moslab qurilgan.

---

## 📝 Loyiha haqida

Ushbu veb-sayt bir nechta asosiy bo'limlardan (Bosh sahifa, Men haqimda, Ko'nikmalar, Loyihalar va Aloqa paneli) iborat bo'lib, tashrif buyuruvchilarga dasturchining salohiyatini vizual va tizimli tarzda ko'rsatib beradi. Sahifada qorong'u/yorug' fon rejimlari (Dark/Light Mode) hamda kubik 3D texnologik animatsiyalar qamrab olingan.

---

## 📐 Sahifa Strukturasi va Navigatsiya Arxitekturasi (DOM Structure)

Veb-sayt bir sahifali (Single Page Application) tuzilishga ega bo'lib, bo'limlararo bog'liqlik quyidagi iyerarxiya asosida ishlaydi:

1. [ Header & Nav ] ──► Dinamik menyu va Kecha/Kunduz rejimi tugmasi (`.mode-toggle`).
2. [ Home Section ] ──► Matnli animatsiyalar, ijtimoiy tarmoqlar havolalari va CV yuklab olish tizimi.
3. [ About Section ] ──► 3D aylanuvchi texnologiyalar kubigi (`.cube`) va umumiy rezyume matni.
4. [ Skills & Projects ] ──► Grid tizimida joylashgan kartochkalar va loyihalar galereyasi.
5. [ Contact Form ] ──► Foydalanuvchilar to'g'ridan-to'g'ri xabar qoldirishi uchun interaktiv shakl.

---

## ⚡ Asosiy xususiyatlari (Features)

* 🌓 **Adaptive Theme Toggle:** `FontAwesome` quyosh/oy ikonkalari va JavaScript orqali boshqariladigan Dark/Light Mode tizimi.
* 📦 **3D Interactive Cube:** "Men haqimda" bo'limida asosiy texnologiyalar (HTML5, CSS3, JS, Python, React) ikonkalari bilan aylanuvchi interaktiv 3D kubik animatsiyasi.
* 📱 **Mobile-First Responsiveness:** `#menu-icon` (hamburg menyu) va CSS Media Queries yordamida smartfon, planshet va kompyuter ekranlariga mukammal moslashuv.
* 📜 **Smooth Scroll & Active Navigation:** Foydalanuvchi sahifani pastga tushirganda, joriy bo'limga qarab navigatsiya menyusidagi tugmalarning avtomatik faollashishi (`.active`).
* 📥 **Native CV Downloader:** HTML5 `download` atributi orqali foydalanuvchiga rezyume faylini (PDF) bir klikda yuklab olish imkoniyatini berishi.

---

## 🛠️ Texnologiyalar (Tech Stack)

* **HTML5** — Semantik arxitektura (`<header>`, `<nav>`, `<section>`, `<footer>`).
* **CSS3 (Advanced Styles)** — Flexbox, CSS Grid, `@keyframes` animatsiyalari, 3D transformatsiyalar va o'zgaruvchilar.
* **FontAwesome (v6.0.0)** — Minimalistik va zamonaviy vektor ikonkalari to'plami.
* **Vanilla JavaScript** — Menyu holatini boshqarish va UI rejimlari dinamikasi.

---

## 🚀 Ishga tushirish (How to Run)

Loyiha hech qanday qo'shimcha paketlar yoki server konfiguratsiyalarini talab qilmaydi:

1. Repozitoriyni kompyuterga yuklab oling:
   ```bash
   git clone [https://github.com/orgkamolbek/personal-portfolio.git](https://github.com/orgkamolbek/personal-portfolio.git)
