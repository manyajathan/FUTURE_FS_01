# 🌐 Dynamic Personal Portfolio

A sleek, responsive, single-page portfolio website designed to showcase foundational frontend development skills, project highlights, and user communication channels. This project utilizes semantic markup, custom component styling, interactive micro-animations, and client-side JavaScript logic.

---

## ✨ Key Features

* **Responsive Grid & Flexbox Layouts:** Designed with a mobile-first mindset. The skills section and form inputs dynamically shift layouts using CSS media queries when viewports scale down below `600px`.
* **Interactive Micro-Animations:** Skill badges feature smooth, hardware-accelerated transitions (`transform: scale(1.05)`) and color shifts upon user hover.
* **Custom Form Elements:** Form fields are optimized with strict box-sizing resets (`box-sizing: border-box`), custom focus outlines, and vertical alignment wrappers.
* **Client-Side Scripting Validation:** Features integrated JavaScript triggers that capture form interactions and deliver visual verification metrics.

---

## 🛠️ Technical Stack

* **HTML5:** Semantic architecture including structured headers (`<h1>`, `<h2>`), interactive lists (`<ul>`, `<li>`), and native forms.
* **CSS3:** Native styling incorporating linear gradients (`#74ebd5` to `#9face6`), flexbox positioning, hover state selectors, and `@media` responsive breakpoints.
* **JavaScript (ES6):** Action-based event scripting used to execute interactive visual workflows.

---

## 📁 File Structure & Implementation Details

* **`index.html`**
    * Establishes the document structure and typography hierarchy.
    * Houses the functional contact matrix (`<form>`) with dedicated inputs for `name`, `email`, and an auto-adjusting message box (`<textarea>`).
* **`style.css`**
    * Defines global layout rules, typography adjustments, and section-specific visual styles.
    * Injects clean left-border visual accents (`border-left: 6px solid #4a63e7`) on section headings to establish visual hierarchy.
    * Maintains layout responsiveness via media break-points for fluid cross-device support.
* **`script.js`**
    * Contains the application logic processing instructions.
    * Executes the `showMessage()` function to simulate successful form processing and feedback loops.

---

## 🚀 Local Installation & Deployment

To launch and run this project locally on your machine:

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
