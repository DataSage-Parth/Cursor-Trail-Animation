# Cursor Trail Effect 🎨

A fluid, animated cursor trail effect built using HTML5 Canvas and JavaScript. As you move your mouse or finger across the screen, multiple smooth, ribbon-like trails follow, creating a dynamic and mesmerizing motion.

> Created by [DataSage-Parth](https://github.com/DataSage-Parth)

---

## 📁 Files

- `index.html` — HTML canvas setup and script inclusion.
- `script.js` — Core logic for pointer tracking and animation.
  
---

## 🚀 Features

- 🖱️ Mouse and Touch support  
- 🎨 Smooth trail animation using spring dynamics  
- 📱 Fully responsive to screen size and orientation  
- 🌈 Dynamic color shifting using sine wave oscillator

---

## 🔧 Configuration

Inside `script.js`, animation parameters can be customized via the `E` object:
```js
const E = {
  debug: true,
  friction: 0.5,
  trails: 20,
  size: 50,
  dampening: 0.25,
  tension: 0.98,
};
