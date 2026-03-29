# 🛡️ Caesar Cipher Studio v3.0

**Caesar Cipher Studio** is an advanced, interactive web-based tool designed for encrypting, decrypting, and cracking one of the most iconic ciphers in history. Built with a focus on seamless **UI/UX** and a futuristic **"Cyber-Visual"** aesthetic.



---

## ✨ Key Features

* **🌍 Full Bi-Directional Language Support:** Optimized for both English (A-Z) and Hebrew (א-ת) alphabets. The engine automatically adjusts the rotation logic based on the selected language.
* **⚡ Integrated Brute Force Engine:** A dedicated "Hacker Mode" that tests all possible keys simultaneously and displays them in a clean, scannable grid for rapid plaintext recovery.
* **🎨 Cyber-Visual Interface:** A high-end "Glassmorphism" design featuring dynamic grid lines, pulsing status indicators, and neon-glow effects.
* **📊 Real-Time Control:** Interactive shift-key selection via a custom range slider with immediate visual feedback.
* **📋 Developer Utilities:** Live character counting, a system session clock, and a "One-Click" copy-to-clipboard feature for processed data.

---

## 🛠️ Tech Stack

* **HTML5** – Semantic structure for modern web standards.
* **CSS3** – Custom properties (Variables), Flexbox/Grid layouts, and Backdrop Filters for the translucent "Glass" effect.
* **Vanilla JavaScript** – Pure cryptographic logic without external dependencies, ensuring high performance and security.
* **Google Fonts** – Featuring `Syne` for bold typography and `JetBrains Mono` for a technical, terminal-like feel.

---

## 🚀 Quick Start

1.  Clone or download the `index.html` file.
2.  Open the file in any modern web browser (Chrome, Edge, or Firefox).
3.  Input your message, select your shift key, and start encrypting!

---

## 🧪 Cryptographic Logic

The encryption follows the mathematical formula for each character $x$ and shift $n$:

$$E_n(x) = (x + n) \pmod{\text{AlphabetSize}}$$

The algorithm is designed to be **non-destructive**, meaning punctuation, numbers, and special characters remain untouched while only alphabetic characters are shifted.

---

## 👨‍💻 Developed By

**Omer Stamker** *Computer Science Student & Cybersecurity Enthusiast*

---

> **Note:** This tool was developed for educational purposes to demonstrate the importance of modern encryption standards by showing how easily classical ciphers can be compromised via automation.
