<div align="center">

# 🚀 Hi, I'm Ahmed Yasser

### Junior Front-End Software Engineer | 15 Years Old

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![PostCSS](https://img.shields.io/badge/PostCSS-DD3A0A?style=for-the-badge&logo=postcss&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Command Line](https://img.shields.io/badge/Command_Line-4D4D4D?style=for-the-badge&logo=windows-terminal&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

</div>

### 👤 The Engineering Mindset (About Me)

I’m **Ahmed**, a **Junior Front-End Software Engineer**. At 15, my approach goes beyond merely writing code; I engineer scalable, high-performance web solutions. Over the past **7 months**, I have dedicated **8 to 10 hours daily** (accumulating over 1,600+ hours of deep, focused coding) to mastering the complexities of the front-end ecosystem and the browser rendering engine.

In a record time of **just two months, I have successfully completed and deployed 15 distinct projects** (including 6 full-scale Applications/Landing Pages and 9 rigorous Frontend Mentor challenges).

**My Quality Baseline:**

- 🎯 **90%+ Pixel-Perfect Accuracy:** Bridging the gap between design and code flawlessly.
- ⚡ **The "400 Club" Standard:** I refuse to deploy unoptimized code. My recent projects guarantee 100/100 scores across **Performance, Accessibility, Best Practices, and SEO**.

---

### ⚙️ Under The Hood: Browser Architecture & The CRP

I don't just write HTML/CSS; I engineer how the browser interprets and paints it. My entire development lifecycle is strictly governed by a deep understanding of the **Browser Rendering Pipeline (BRP)** and the **Critical Rendering Path (CRP)**. Here is how I optimize every step of the rendering engine:

- **1. Parsing (DOM & CSSOM Generation):** I write shallow, highly semantic HTML to ensure rapid construction of the **Document Object Model (DOM)**. Simultaneously, I utilize utility-first frameworks (like Tailwind) and purge unused styles to keep the **CSS Object Model (CSSOM)** extremely lightweight, preventing the CSS engine from blocking the main thread.
- **2. The Render Tree Architecture:** I understand that the browser combines the DOM and CSSOM to create the **Render Tree** (which only contains visible elements). By strategically structuring my HTML and using `display: none` for non-critical off-canvas elements, I ensure the browser doesn't waste memory calculating nodes that the user cannot currently see.
- **3. Layout (Reflow) Prevention:** I know exactly which CSS properties trigger geometry calculations. I actively avoid animating layout-triggering properties (like `width`, `height`, `margin`, or `top`/`left`) to prevent expensive synchronous "Reflows" that cause layout thrashing and jittery UI.
- **4. Paint (Repaint) Optimization:** To minimize the pixels the browser has to redraw during interactions (like hover states), I rely on modern CSS patterns and state lifting, avoiding heavy background-color repaints over massive areas when possible.
- **5. GPU Compositing (Hardware Acceleration):** This is where my UI achieves a rock-solid **60 FPS**. I exclusively use `transform` and `opacity` for UI animations. Coupled with the strategic use of `will-change`, I bypass the Layout and Paint phases entirely, pushing the rendering workload to isolated layers on the GPU (Compositor Thread).

---

### 🏛️ Advanced UI/UX Concepts

- **Strict DOM Semantics (The "Bag" Mental Model):** I strictly enforce W3C HTML semantics to guarantee 100% Screen Reader accessibility. I navigate list structures using the **"Container Bag"** mental model: The `<ul>` is an outer bag designed to hold only one type of item—the `<li>` (the inner carrier bag). You cannot throw random items directly into the outer bag. 
- **Grid Mathematics (`auto-fit` vs `auto-fill`):** By strategically utilizing `auto-fit`, I force the rendering engine to act as a visual garbage collector—collapsing empty "phantom" columns so flexible units (`1fr`) can flawlessly distribute space without layout fragmentation on ultra-wide screens.
- **Zero-JS State Management:** I actively reduce JavaScript payloads by pushing state mutations entirely to the CSS engine via CSS State Lifting, the `:has()` pseudo-class, and the `peer` combinator.

---

### 🏆 Latest Project Spotlight: The Elite Admin Dashboard

As concrete proof of my engineering mindset, my most recent and complex architecture—the **8-page Elite Admin Dashboard**—shattered performance benchmarks. 

By meticulously optimizing the Critical Rendering Path and enforcing strict GPU-accelerated animations, I achieved a flawless **100/100 across all four Lighthouse metrics** with a **0ms Total Blocking Time (TBT)**. More importantly, I engineered a rock-solid DOM layout that achieves a **0 Cumulative Layout Shift (CLS)** across the entire application, alongside sub-half-second First Contentful Paint (FCP).

<div align="center">

![Elite Admin Dashboard Hero](hero.png)

---

![Dashboard Lighthouse Score 100](header.png)

---

![Dashboard Lighthouse Metrics 0 CLS](header2.png)

</div>

---

### 📂 Featured Projects (The Gallery)

| Project Preview                                 | Details                                                                                                                                                                                                                                                                                                      |
| :---------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Elite Dashboard](hero.png)                    | 🌟 **Elite Admin Dashboard**<br>An advanced, meticulously engineered 8-page dashboard. Achieved a flawless 100/100 Lighthouse score on every single page with 0 CLS.<br>🔗 [Live Demo](https://ahmed-let-front.github.io/Dashboard-01/) \| [Repo](https://github.com/Ahmed-let-front/Dashboard-01) |
| ![Modern Agency Template](template-web-3.png)   | **Modern Agency Template (Web 3)**<br>Built entirely with Tailwind CSS. Scored a flawless 100% across all metrics.<br>🔗 [Live Demo](https://ahmed-let-front.github.io/teamplate-web-3/) \| [Repo](https://github.com/Ahmed-let-front/teamplate-web-3.git)                                               |
| ![RIS Landing Hoodie](RIS.png)                  | **RIS Landing Hoodie (Tailwind v4)**<br>Refactored for maximum performance and clean utility classes.<br>🔗 [Live Demo](https://ahmed-let-front.github.io/RIS-hoodie/) \| [Repo](https://github.com/Ahmed-let-front/RIS-hoodie.git)                                                                      |
| ![Clipboard Landing Page](landing-mentor.png)   | **Clipboard Landing Page**<br>A fully responsive, complex landing page crafted with precise semantic HTML and flexbox layouts. Achieved >95% pixel-perfect matching.<br>🔗 [Live Demo](https://ahmed-let-front.github.io/landing-page-in-frontend-mentor/) \| [Repo](https://github.com/Ahmed-let-front/landing-page-in-frontend-mentor.git) |
| ![Agency Landing Page](leon.png)                | **Agency Landing Page (Leon)**<br>A professional multi-section template built from scratch.<br>🔗 [Live Demo](https://ahmed-let-front.github.io/leon-template/) \| [Repo](https://github.com/Ahmed-let-front/leon-template)                                                                              |
| ![Creative Agency](kasper.png)                  | **Creative Agency (Kasper)**<br>Modern landing page focusing on high-fidelity UI.<br>🔗 [Live Demo](https://ahmed-let-front.github.io/kasper-template-tow/) \| [Repo](https://github.com/Ahmed-let-front/kasper-template-tow)                                                                            |
| ![Chat App CSS Illustration](chat-app.jpg)      | **Chat App CSS Illustration**<br>Demonstrating advanced CSS layout techniques to build a responsive, complex mobile chat UI from scratch.<br>🔗 [Live Demo](https://ahmed-let-front.github.io/chat-app/) \| [Repo](https://github.com/Ahmed-let-front/chat-app.git)                                      |
| ![Result Summary Component](summary-result.jpg) | **Result Summary Component**<br>A micro-interaction component focusing on clean UI, absolute positioning, and perfect spacing.<br>🔗 [Live Demo](https://ahmed-let-front.github.io/result-summary-component-main/) \| [Repo](https://github.com/Ahmed-let-front/result-summary-component-main)         |
| ![Bento Grid Layout](bento-grid.png)            | **Bento Grid Layout**<br>Mastering complex CSS Grid placements and responsive alignment.<br>🔗 [Live Demo](https://ahmed-let-front.github.io/bento-grid-front-end-mentor-/) \| [Repo](https://github.com/Ahmed-let-front/bento-grid-front-end-mentor-)                                                   |
| ![Testimonials Grid](testmonials.png)           | **Testimonials Grid**<br>Mobile-first layout with custom shadow effects and clean typography.<br>🔗 [Live Demo](https://ahmed-let-front.github.io/testmonials/) \| [Repo](https://github.com/Ahmed-let-front/testmonials)                                                                                |
| ![Product Preview Card](chanel.png)             | **Product Preview Card**<br>Focused on art direction and responsive image switching.<br>🔗 [Live Demo](https://ahmed-let-front.github.io/product-chanel/) \| [Repo](https://github.com/Ahmed-let-front/product-chanel)                                                                                   |
| ![Recipe Page](recipe.png)                      | **Recipe Page**<br>Organized layout using semantic HTML tables and custom lists.<br>🔗 [Live Demo](https://ahmed-let-front.github.io/recipe/) \| [Repo](https://github.com/Ahmed-let-front/recipe)                                                                                                       |
| ![Social Links Profile](social-links.png)       | **Social Links Profile**<br>Minimalist UI with smooth CSS hover transitions.<br>🔗 [Live Demo](https://ahmed-let-front.github.io/social-links/) \| [Repo](https://github.com/Ahmed-let-front/social-links)                                                                                             |
| ![Four-Card Feature Section](four-product.png)  | **Four-Card Feature Section**<br>Responsive multi-column grid with custom border accents.<br>🔗 [Live Demo](https://ahmed-let-front.github.io/four-product/) \| [Repo](https://github.com/Ahmed-let-front/four-product)                                                                                  |
| ![QR Code Component](qr.png)                    | **QR Code Component**<br>A simple, clean, and fully responsive QR component.<br>🔗 [Live Demo](https://ahmed-let-front.github.io/qr-code-frontend-meentor/) \| [Repo](https://github.com/Ahmed-let-front/qr-code-frontend-meentor)                                                                       |
