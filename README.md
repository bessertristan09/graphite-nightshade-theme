# 🌒 Graphite Nightshade

**A refined and atmospheric dark theme for Home Assistant**, based on the original [Graphite Theme](https://github.com/TilmanGriesel/graphite) by Tilman Griesel — and reimagined by [Tristan Besser](https://github.com/bessertristan09).

Graphite Nightshade features a deep, modern color palette, soft edges, and clean typography using the *Figtree* font (also used on [home-assistant.io](https://www.home-assistant.io)). It supports all major UI elements including the new `ha-*` tokens for CSS fonts, Mushroom cards, and Code Editor themes.

---

## ✨ Features

- Dark mode only – no compromises
- Smooth and subtle background layers
- Carefully chosen colors with soft gradients
- `ha-*` token support (Home Assistant 2025.5+)
- Fully compatible with:
  - Mushroom UI
  - Mini Graph Card
  - Code Editor (incl. syntax highlighting)
- Custom font: [Figtree](https://fonts.google.com/specimen/Figtree)

---

## 📸 Screenshots

*(Add some screenshots here later if you want to show off your style!)*

---

## 📦 Installation

1. **Add this repository to HACS:**
   - Go to HACS → Frontend → Click the three dots menu → *Custom repositories*
   - Add: `https://github.com/bessertristan09/graphite-nightshade`
   - Category: `Theme`

2. **Install the theme**

3. **Enable in your `configuration.yaml` if not already done:**

   ```yaml
   frontend:
     themes: !include_dir_merge_named themes
   ```

4. **Select the theme in your user profile:**  
   → *Profile → Themes → Graphite Nightshade*

---

## 💡 Requirements

- Home Assistant Core `2025.5.0` or higher (for full `ha-*` token support for fonts)
- [card-mod](https://github.com/thomasloven/lovelace-card-mod) (optional, but recommended)

---

## 📜 License

Released under the **MIT License**  
Copyright (c):

- 2022 Tilman Griesel  
- 2025 Tristan Besser

See [LICENSE](LICENSE) for full details.

---

Made with ❤️ & `rgba(22, 24, 29, 0.99)`  
by [Tristan Besser](https://github.com/bessertristan09)

> May your UI be as smooth as your automations 😎
