# 🌒 Graphite Nightshade

![Release](https://img.shields.io/github/v/release/bessertristan09/graphite-nightshade-theme?style=for-the-badge&color=4169E1)
![Contributors](https://img.shields.io/github/contributors/bessertristan09/graphite-nightshade-theme?style=for-the-badge&color=4169E1)
![License](https://img.shields.io/badge/License-MIT-darkgreen?style=for-the-badge)
![Maintained](https://img.shields.io/badge/maintained-yes-darkgreen?style=for-the-badge)

**A refined and atmospheric dark theme for Home Assistant**, based on the original [Graphite Theme](https://github.com/TilmanGriesel/graphite) by [Tilman Griesel](https://github.com/TilmanGriesel) — and reimagined by [Tristan Besser](https://github.com/bessertristan09).

Graphite Nightshade features a deep, modern color palette, soft edges, and clean typography using the *Figtree* font (also used on [home-assistant.io](https://www.home-assistant.io)).  
It supports all major UI elements including the new `ha-*` tokens, Mushroom cards, and code editor styling.

---

## ✨ Features

- 🖤 Dark mode only — no compromises
- 🎨 Smooth background layers & soft gradients
- 🧠 `ha-*` token support (HA 2025.5+)
- 🔤 Clean Google Font: [Figtree](https://fonts.google.com/specimen/Figtree)
- ✅ Fully compatible with:
  - Mushroom UI
  - Mini Graph Card
  - Code Editor (incl. syntax highlighting)

### 📱 Variants of this Theme

<details>
<summary><strong>Graphite Nightshade</strong> vs. <strong>Graphite Nightshade App-Theme</strong> — What's the difference?</summary>

#### Graphite Nightshade (Default)
- Transparent top navigation bar  
- Immersive look (ideal for dashboards with full-screen wallpapers)
<p align="center">
  <img src="https://github.com/user-attachments/assets/541a1570-01a1-47f1-b6b7-686f7dadf6fd" width="80%" alt="Gradient View">
  <br><sub>🌈 Graphite Nightshade with transparent navbar</sub>
</p>

#### Graphite Nightshade App-Theme
- Solid navbar background  
- Better visibility when scrolling, especially on small/mobile displays  
- Recommended for iOS or complex dashboards
<p align="center">
  <img src="https://github.com/user-attachments/assets/3d36cdc4-7e36-4c06-bedf-ff0ccf4eba51" width="80%" alt="Gradient View">
  <br><sub>🌈 Graphite Nightshade App-Theme with solid dark navbar</sub>
</p>
</details>

---

## 📸 Screenshots

<p align="center">
  <img src="https://github.com/user-attachments/assets/d44a54b8-cd72-45da-982f-d33955de9400" width="80%" alt="Classic View">
  <br><sub>💡 Classic dark mode without wallpaper</sub>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b8ab1677-8891-43e2-abd4-ccbb5dd103a4" width="80%" alt="Gradient View">
  <br><sub>🌈 Graphite Nightshade with gradient wallpaper and sidebar</sub>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b216cc8b-7f2f-41c9-84a7-505d6f8615be" width="80%" alt="Card View">
  <br><sub>📊 Card detail view with VOC index curve</sub>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/143479c3-73e0-4194-a0f0-9cca043e0624" width="80%" alt="Energy Dashboard">
  <br><sub>🌈 Energy Dashboard with vibrant color accents</sub>
</p>

---

## 💡 Requirements

- Home Assistant Core `2025.5.0` or higher  
  (for full support of `ha-*` typography tokens)

### 🧩 Optional (but recommended): Local Font Installation

If your browser fails to load the [Figtree](https://fonts.google.com/specimen/Figtree) font reliably (especially outside dashboards),  
install it locally as a fallback:

👉 [FONT-INSTALL.md – Click here](./FONT-INSTALL.md)

---

## 📦 Installation Guide

<details>
<summary>Click to expand</summary>

### 1. Install HACS (if not already)

Follow the [official HACS setup guide](https://hacs.xyz/docs/setup/download/).

### 2. Add this Theme Repository to HACS

**Option A — Manually:**

- Go to **HACS → Frontend**
- Open the menu (⋮) → *Custom repositories*
- Add:  
  `https://github.com/bessertristan09/graphite-nightshade`  
  Category: `Theme`

**Option B — My Home Assistant link:**  
[![Add via My Home Assistant](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=bessertristan09&repository=graphite-nightshade-theme&category=theme)

### 3. Install the Theme via HACS

Search for **Graphite Nightshade** in HACS Frontend section and install.

### 4. Enable Themes in `configuration.yaml`

```yaml
frontend:
  themes: !include_dir_merge_named themes
```

### 5. Select the Theme in Your Profile

Go to  
**Profile → Themes → Select: Graphite Nightshade**

### 6. Add Figtree Font as Resource

1. Go to `Configuration → Lovelace Dashboards`  
2. Switch to the **Resources** tab  
3. Click `+ Add Resource`  
4. Add this URL as a **Stylesheet**:

```css
https://fonts.googleapis.com/css2?family=Figtree:wght@300..900&display=swap
```

### 7. Restart Home Assistant

After everything is set, **restart your HA server** to apply the changes.

</details>

---

## 📜 License

Released under the **MIT License**  
Copyright:

- © 2022 – Tilman Griesel  
- © 2025 – Tristan Besser

See [`LICENSE`](./LICENSE) for full details.

---

<p align="center">
  Made with ❤️ & <code>rgba(22, 24, 29, 0.99)</code>  
  <br>by <a href="https://github.com/bessertristan09">Tristan Besser</a>
</p>

> _May your UI be as smooth as your automations 😎_
