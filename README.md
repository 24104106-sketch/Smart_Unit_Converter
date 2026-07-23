# 📐 Smart Unit Converter

A modern, responsive, and professional **Unit Converter web application** built with pure **HTML, CSS, and JavaScript** — no frameworks, no libraries, no backend. Designed with a glassmorphism aesthetic and full light/dark mode support, this project is ideal as a college mini project or a personal utility tool.

---

## 🚀 Project Overview

Smart Unit Converter lets users instantly convert values across seven common categories — Length, Weight, Temperature, Time, Speed, Area, and Volume. It performs **live conversion** as you type, remembers your last 10 conversions using **Local Storage**, and lets you copy results with a single click. The entire app runs client-side and works simply by opening `index.html` in any modern browser.

---

## ✨ Features

- **7 Unit Categories** — Length, Weight, Temperature, Time, Speed, Area, and Volume
- **Live Conversion** — results update instantly as you type, no page reloads
- **Swap Button** — instantly flips the "From" and "To" units
- **Conversion History** — stores the last 10 conversions in Local Storage with a clear button
- **Copy Result** — copies the converted value to your clipboard with a success toast
- **Formula Display** — shows the exact mathematical formula used for every conversion
- **Reset Button** — clears input, dropdowns, and results in one click
- **Light / Dark Mode** — toggle theme, preference saved in Local Storage
- **Input Validation** — friendly error messages for invalid or non-numeric input, decimals supported
- **Fully Responsive** — optimized layouts for desktop, tablet, and mobile
- **Smooth Animations** — hover effects, card entrance animation, result fade-in, swap spin, theme transitions
- **Professional Footer** — project name, version, and current year

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5**  | Semantic structure and accessibility |
| **CSS3**   | Glassmorphism design, responsive layout, animations, theming via CSS variables |
| **JavaScript (ES6+)** | Conversion logic, DOM manipulation, Local Storage, Clipboard API |

No external frameworks, libraries, or backend servers are used.

---

## 📂 Folder Structure

```
Smart_Unit_Converter/
│
├── index.html      # Main HTML structure (semantic markup, form, history panel)
├── style.css        # All styling: theme variables, glassmorphism cards, responsive rules, animations
├── script.js        # Conversion logic, event handling, Local Storage, theme toggle
└── README.md         # Project documentation (this file)
```

---

## ▶️ How to Run the Project

1. **Download / Extract** the `Smart_Unit_Converter` folder from the ZIP file.
2. Open the folder and **double-click `index.html`** — it will open directly in your default web browser.
3. That's it! No installation, no build steps, no server required.

> Optional: For the best experience with the Clipboard API (Copy Result feature), you can serve the folder using a simple local server (e.g. VS Code "Live Server" extension), though it also works fine when opened directly as a file in most browsers.

---

## 🔢 Supported Conversions

| Category | Units Included |
|----------|----------------|
| Length | Kilometer, Mile, Meter, Foot, Centimeter, Inch |
| Weight | Kilogram, Pound, Gram, Ounce |
| Temperature | Celsius, Fahrenheit, Kelvin |
| Time | Second, Minute, Hour |
| Speed | Km/h, m/s |
| Area | Square Meter, Square Foot |
| Volume | Liter, Milliliter |

Any unit within a category can be converted to any other unit in that same category (not just the highlighted pairs above).

---

## 🔮 Future Enhancements

- Add more categories (Data Storage, Pressure, Energy, Currency with live exchange rates)
- Export conversion history as CSV/PDF
- Add keyboard shortcuts for swap and reset
- Add a "favorite conversions" pinning feature
- Support multi-language UI
- Add PWA support for offline installation on mobile devices
- Voice input for entering values

---

## 📄 Version

**Version 1.0** — Initial release.

---

Built with ❤️ using only HTML, CSS, and JavaScript.
