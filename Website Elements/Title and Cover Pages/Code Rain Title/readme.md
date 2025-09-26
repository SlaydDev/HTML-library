# Matrix Loader

This snippet creates a **Matrix-style intro animation** featuring:
- Raining green code (Matrix effect)
- A glowing falling ball
- A sleek animated loading bar
- A final reveal of your custom text

Perfect as a loading screen or website intro effect.

---

## 🔧 How to Use

### Method 1: Embed into a Site Builder
1. Open your site builder (e.g., Wix, Squarespace, WordPress with custom code blocks).
2. Copy and paste the full HTML/CSS/JS code into a **custom code block**.
3. Save and preview your site.

### Method 2: Pure HTML/CSS/JS
1. Download the `matrix-loader.html` file.
2. Open it in your browser, or copy the code into your existing project.
3. Adjust styles and text as needed.

---

## 🎨 What You Can Change

### 1. Colors (line ~25)
Edit the CSS variables to match your theme:

:root {
  --ball:#3b82f6;   /* Main ball color */
  --rim:#93c5fd;    /* Text outline color */
  --glow:#60a5fa;   /* Glow color */
  --accent:#8b5cf6; /* Accent gradient color */
}

---

### 2. Title Text (line ~157)
Update the text that appears after loading:

<div class="title">YOUR_TEXT_HERE</div>

Replace `YOUR_TEXT_HERE` with your own message.

---

### 3. Matrix Characters & Density (JavaScript section)
Modify which characters fall and how many lines appear:

const characters = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789'; // characters used
const numberOfDrops = 100; // number of rain lines

- Change `characters` to add symbols or letters.
- Adjust `numberOfDrops` for more or less rain.

---

### 4. Animation Durations
Fine-tune how fast things happen:
- **Loading bar:** `@keyframes loadingFill` (`4s`)
- **Typing effect:** `@keyframes typing` (`4s`)
- **Ball fall:** `@keyframes fall` (`1.2s`)

---

## ⚠️ Important Notice
Please **do not remove the credits** from this snippet.
Respecting credits helps keep this library free and open for everyone.

---

**Designed by [Slayd Dev](https://github.com/slayddev)**

