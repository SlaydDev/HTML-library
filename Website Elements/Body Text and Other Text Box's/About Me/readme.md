# Animated About Section

This snippet creates an **animated About section** for your website, featuring:
- Smooth fade-in text paragraphs
- Highlighted key messages
- Stylish layout centered on the page

Perfect for personal websites, portfolios, or project landing pages.

---

## 🔧 How to Use

### Method 1: Embed into a Site Builder
1. Open your site builder (e.g., Wix, Squarespace, WordPress with custom code blocks).
2. Copy and paste the HTML/CSS code into a **custom code block**.
3. Save and preview your site.

### Method 2: Pure HTML/CSS
1. Download the `about-section.html` file.
2. Open it in your browser, or copy the code into your project.
3. Customize the text and colors as needed.

---

## 🎨 What You Can Change

### 1. Text Content (lines ~43–46)
Update the paragraphs with your own information:

<p>Hi, I’m [YOUR_NAME] — [YOUR_DESCRIPTION].</p>
<p>[WELCOME_MESSAGE]</p>
<p><strong>[IMPORTANT_NOTE]</strong></p>
<p>[CLOSING_MESSAGE]</p>

- `[YOUR_NAME]` → Your name  
- `[YOUR_DESCRIPTION]` → Short description about you or the site  
- `[WELCOME_MESSAGE]` → Intro or welcome message  
- `[IMPORTANT_NOTE]` → Highlighted note (optional, e.g., “Under construction”)  
- `[CLOSING_MESSAGE]` → Final sign-off or thank you message

---

### 2. Highlight Color (line ~18)
Change the `--highlight` CSS variable to customize the color of important text:

--highlight: #3b82f6; /* Highlight color */

---

### 3. Animation Timings
You can adjust the fade-in delays by editing the `animation-delay` values in the CSS:

- `.text p:nth-child(1)` → delay for first paragraph  
- `.text p:nth-child(2)` → delay for second paragraph  
- `.text p:nth-child(3)` → delay for highlighted paragraph  
- `.text p:nth-child(4)` → delay for closing paragraph  

---

## ⚠️ Important Notice
Please **do not remove the credits** from this snippet.  
Respecting credits helps keep this library free and open for everyone.

---
**Designed by [Slayd Dev](https://github.com/slayddev)**
