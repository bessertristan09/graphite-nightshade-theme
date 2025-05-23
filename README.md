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

<p align="center">
  <img src="https://github.com/user-attachments/assets/d44a54b8-cd72-45da-982f-d33955de9400" width="80%"><br>
  <sub>💡 Classic dark mode without wallpaper</sub>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b8ab1677-8891-43e2-abd4-ccbb5dd103a4" width="80%"><br>
  <sub>🌈 Graphite Nightshade with gradient wallpaper and sidebar</sub>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b216cc8b-7f2f-41c9-84a7-505d6f8615be" width="80%"><br>
  <sub>📊 Card detail view with VOC index curve</sub>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/143479c3-73e0-4194-a0f0-9cca043e0624" width="80%"><br>
  <sub>🌈 Energy Dashboard with some nice colors for various devices</sub>
</p>



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

## 🔣 Font:
**This theme uses 1 custom font via Google Fonts, you will need to add this as a resource in order to use the same fonts.**
1. Click on ```configuration``` within Home Assistant
2. Click on ```Lovelace Dashboards```
3. Click the ```Resources``` tab at the top
4. Click the ```+ Add Resource``` button
5. You will need to add the following URL and set the *resource type* to ```Stylesheet```, then click on ```create```.
   *URL to copy*:

    ```CSS
    https://fonts.googleapis.com/css2?family=Figtree:wght@300..900&display=swap
    ``` 
   
6. Once the above is complete, you will **need to restart your Home Assistant server** for the changes to come into affect.

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
