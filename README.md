# Personal Portfolio Website — Rajkumar Lokadhyaksha

A modern, high-end editorial portfolio website designed and developed from scratch using **Semantic HTML5** and **Custom CSS3**, referencing modern minimalist product design standards.

---

## 👨‍💻 Author

* **Name:** Rajkumar Lokadhyaksha
* **Institution:** Scaler School of Technology (2026–2030)
* **Degree:** BITS Pilani — B.Sc. (Hons) in Computer Science & Artificial Intelligence
* **Location:** Bengaluru, Karnataka & Pilani, Rajasthan

---

## 📖 About The Project

This website was created as part of the **Builders Day Challenge** (Web Development Course). The goal was to build a clean, responsive, functional, and personal portfolio that introduces the developer, showcases core technical skills, and features completed academic and software engineering projects.

The design faithfully replicates modern editorial aesthetics:
1. **Hero Section:** Bold display typography (`Software Engineer`), developer vector portrait card, introductory bio, and interactive brand/tech pills.
2. **About Me Section:** Large editorial headlines, an interactive showcase mockup card with a play button, and highlighted achievement statistics (`+320`, `+280`).
3. **Services / What I Offer:** Split layout with a 2x2 grid featuring a standout **dark themed card** with a diagonal arrow (`↗`).
4. **Experience & Education:** Yearly progression timeline with interactive hover states highlighting Scaler School of Technology and BITS Pilani.
5. **Portfolio & Selected Works:** 6-card grid (3x2) with sleek device mockups, tags, descriptions, and direct live links to course assignments.
6. **Contact Section:** Clean contact cards and a responsive inquiry form.
7. **Footer:** Quick navigation links, copyright, and smooth back-to-top scroll.

---

## 🛠️ Technologies Used

* **HTML5:** Semantic elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`, `<form>`, `<table>`)
* **CSS3:**
  * **Flexbox:** Navigation bar, hero layout, button groups, experience list rows, footer
  * **CSS Grid:** Services 2x2 cards, portfolio 3-column project gallery, contact split layout
  * **CSS Box Model:** Precision margins, paddings, borders, and border-radius tokens
  * **Positioning:** Sticky navigation bar (`position: sticky`), z-index layering, floating tags
  * **Transitions & Animations:** Smooth cubic-bezier hover states (`transition: all 0.35s`), floating portrait badge (`@keyframes floatGentle`), glowing indicator dot (`@keyframes pulseDot`)
  * **Responsive Design:** Media queries (`@media (max-width: 1024px)`, `@media (max-width: 768px)`, `@media (max-width: 480px)`) ensuring flawless rendering on Desktop, Tablet, and Mobile devices.

---

## 📂 Project Directory Structure

```text
web dev/
│
├── index.html               # Main Personal Portfolio Website (Reference Design)
├── style.css                # Custom CSS stylesheet with design tokens, flexbox & grid
├── student-portal.html      # Assignment 01: Semantic Student Portal with forms & tables
├── flexbox-quest.html       # Assignment 02: Flexbox Quest Mini Game UI (Pure Flexbox)
├── README.md                # Project documentation and TA evaluation guide
│
└── images/
    ├── profile.svg          # Rajkumar Lokadhyaksha portrait vector artwork
    ├── about-preview.svg    # Interactive code showcase with play button overlay
    ├── project-1.svg        # Flexbox Quest retro game mockup
    ├── project-2.svg        # Student Portal academic system mockup
    ├── project-3.svg        # AI Algorithm Visualizer neural net mockup
    ├── project-4.svg        # SaaS Productivity dashboard mockup
    ├── project-5.svg        # Mediant Pro Social Media Automation mockup (Dark)
    └── project-6.svg        # Campus Connect student collaboration hub mockup
```

---

## 🚀 Featured Projects

### Project 1: Flexbox Quest — Mini Game UI
* **File:** `flexbox-quest.html` (Accessible via Portfolio Live Demo link)
* **Description:** An interactive retro mini game user interface built strictly using CSS Flexbox without any CSS Grid, absolute positioning, or JavaScript. Includes game header with score/lives counters, centered stage area with player and platforms, control pad, 4-slot inventory, and quest panel.
* **Concepts Demonstrated:** `display: flex`, `flex-direction`, `justify-content`, `align-items`, `flex-wrap: wrap`, `flex: 1`, box model, responsive media query.

### Project 2: Student Portal Web App
* **File:** `student-portal.html` (Accessible via Portfolio Live Demo link)
* **Description:** Academic student portal built using pure semantic HTML and introductory CSS. Features an enrolled student profile table with a "Top Performer" badge, weekly class timetable table, and a course registration form with inputs, select dropdown, radio buttons, and checkboxes.
* **Concepts Demonstrated:** Semantic tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`), `<table>`, `<th>`, `<tr>`, `<td>`, `<form>`, `<label>`, `<select>`, radio buttons, checkboxes, element, class, and ID selectors.

### Project 3: AI & Algorithm Visualizer
* **Description:** Research simulation visualizing graph traversals (Breadth-First and Depth-First Search), neural network layers, and algorithmic computational complexity for computer science coursework.

### Project 4: SaaS Analytics Platform
* **Description:** Responsive web productivity dashboard with agile sprint trackers, team velocity bar charts, and CSS-driven metrics.

### Project 5: Mediant Pro — Social Media Automation Dashboard
* **Description:** Dark-themed social media distribution platform featuring automated campaign metrics, audience growth charts, and real-time scheduling.

### Project 6: Campus Connect Hub
* **Description:** Centralized collaboration portal for Scaler School of Technology and BITS Pilani students to share notes, assignments, and technical discussions.

---

## 🧑‍🏫 TA Evaluation Guide (Answers to Common Questions)

### Q1: Where and why did you use CSS Grid?
> **Answer:** CSS Grid was used for:
> 1. The **Services 2x2 grid** (`grid-template-columns: repeat(2, 1fr)`), because it allows two-dimensional alignment where card heights remain uniform across rows.
> 2. The **Portfolio gallery** (`grid-template-columns: repeat(3, 1fr)` on desktop, adapting to 2 columns on tablet and 1 column on mobile via media queries).
> 3. The **Contact section** (`grid-template-columns: 1fr 1.3fr`) to give the form card appropriate proportional width relative to the contact info column.

### Q2: Where and why did you use Flexbox?
> **Answer:** Flexbox was used for 1-dimensional components:
> 1. The **Navbar** (`display: flex; justify-content: space-between; align-items: center;`) to distribute the logo, navigation links, and CTA pill.
> 2. The **Hero section** to align the giant display title with the photo card and intro bio.
> 3. The **Experience list rows** (`display: flex; justify-content: space-between;`) to place the university details on the left and the date span on the right.
> 4. The **Tech pill strip** (`display: flex; gap: 14px; overflow-x: auto;`) for smooth horizontal scrolling of skill tags.

### Q3: What does `flex: 1` do in your code?
> **Answer:** `flex: 1` is shorthand for `flex-grow: 1; flex-shrink: 1; flex-basis: 0%;`. In the panels and cards, it ensures that child items expand evenly to fill the entire remaining cross/main space within the flex container.

### Q4: Why did you use `position: sticky` on the navigation bar?
> **Answer:** `position: sticky; top: 0; z-index: 1000;` keeps the navigation bar pinned to the top of the viewport when scrolling, allowing visitors to easily navigate between sections without having to scroll all the way back up. The `backdrop-filter: blur(12px)` and translucent background ensure readability over page content.

### Q5: How do the hover effects and transitions work?
> **Answer:** Instead of abrupt state changes, interactive elements use CSS transitions:
> ```css
> .service-card:hover {
>     transform: translateY(-5px);
>     box-shadow: var(--shadow-md);
> }
> ```
> Combining `transform: translateY()` with an easing curve (`cubic-bezier(0.16, 1, 0.3, 1)`) creates a polished floating elevation effect.

### Q6: How is responsive design implemented?
> **Answer:** Responsive design is implemented using CSS Media Queries without external frameworks:
> - At **1024px**, the portfolio grid shifts from 3 columns to 2 columns, and the services layout adjusts.
> - At **768px** (tablets/mobile), multi-column grids become single columns (`flex-direction: column` and `grid-template-columns: 1fr`), title font sizes are scaled down, and padding is adapted to prevent horizontal scrolling.
