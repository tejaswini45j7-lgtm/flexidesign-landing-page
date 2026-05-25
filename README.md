# FlexiDesign - Minimalist Modern Landing Page

A sleek, responsive, and minimalist landing page template designed with modern web standards. Built completely with vanilla HTML, CSS, and a dash of JavaScript, this template features a built-in interactive dark mode toggle powered by CSS custom properties (variables).

---

## 🚀 Features

* **Pure CSS Variables:** Instantly change the theme, brand colors, or typography across the entire page by modifying a single file.
* **Fully Responsive:** Crafted using **CSS Flexbox** and **CSS Grid** to ensure a flawless experience on smartphones, tablets, and desktops.
* **Dark Mode Ready:** Comes standard with a lightweight JavaScript theme controller that toggles dark/light modes smoothly using a `data-theme` HTML attribute.
* **Minimalist Aesthetic:** Clean layouts, heavy reliance on white space, and sharp typographic hierarchies optimized for conversions or portfolios.
* **No Framework Dependency:** Built with **zero** external libraries or build tools—just pure, high-performance web code.

---


### 🎨 Theme Customization

The layout utilizes native CSS custom properties. To change the color palette for either light or dark mode, simply update the variables inside `style.css`
### 💻 Technical Details

#### Mobile-First Layout Transitions
The responsive layout automatically scales font sizes down and simplifies navigation on screens smaller than `768px`. The desktop features grid utilizes `auto-fit` with a `minmax(280px, 1fr)` property, forcing columns to stack beautifully on mobile displays without breaking the grid structure.

#### Theme Engine
The light/dark mode logic uses a lightweight vanilla JavaScript listener that looks for changes on the parent element. 

CSS transitions are applied via the wildcard (`*`) element reset to ensure smooth background-color and text fading when switching themes.

---

### 📝 License

This project is open-source and free to use for personal or commercial projects. Modify it, break it, and build something awesome!
