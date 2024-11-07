# Advanced CSS Styling Project 🎨

> A comprehensive project to master advanced CSS concepts and modern styling techniques.

![CSS Banner](https://i.imgur.com/5bXh2yx.png)

## 🎯 Project Overview

This project explores advanced CSS concepts through a series of progressive tasks, from basic styling to complex animations. We'll build a modern, responsive website while learning essential CSS techniques.

## 🗂️ Project Structure

<div class="mermaid">
graph TB
    A[Project Root] --> B[images/]
    A --> C[styles/]
    B --> D[Profile Pictures]
    B --> E[Article Images]
    B --> F[Work Examples]
    C --> G[Base Styles]
    C --> H[Components]
    C --> I[Themes]
    
    style A fill:#f9f,stroke:#333,stroke-width:2px
    style B fill:#bbf,stroke:#333,stroke-width:2px
    style C fill:#bbf,stroke:#333,stroke-width:2px
</div>

## 📚 Concepts Covered

### 1. CSS Variables & Custom Properties
```css
:root {
    --color-primary: #d73953;
    --text-color: var(--color-black);
    --font-family-title: "Raleway", "Helvetica Neue";
}
```

### 2. Advanced Selectors
- Attribute selectors `[class^="col-"]`
- Pseudo-elements `::before` and `::after`
- Complex combinations

### 3. Responsive Design
<div class="mermaid">
pie
    title "Project Focus Areas"
    "Layout & Grid" : 30
    "Typography" : 25
    "Animations" : 20
    "Colors & Themes" : 15
    "Components" : 10
</div>

## 🛠️ Key Features

### Theme System
```css
[data-section-theme="dark"] {
    --text-color: var(--color-white);
    --section-title-color: var(--color-white);
    background: var(--color-black);
}
```

### Grid System
```css
.row::after {
    content: "";
    display: table;
    clear: both;
}

[class^="col-"] {
    float: left;
    padding: 0.5rem;
}
```

### Animation System
```css
:root {
    --transition-duration: .3s;
    --transition-cubic-bezier: cubic-bezier(0.17, 0.67, 0, 1.01);
}
```

## 📝 Task Breakdown

<div class="mermaid">
gantt
    title Project Tasks Timeline
    dateFormat  YYYY-MM-DD
    section Foundation
    Variables & Setup           :a1, 2024-01-01, 7d
    Grid System                 :a2, after a1, 5d
    section Components
    Navigation                  :b1, after a2, 6d
    Cards & Sections           :b2, after b1, 8d
    section Polish
    Animations                 :c1, after b2, 4d
    Theme Integration          :c2, after c1, 5d
</div>

## 🌟 Highlights

1. **Custom Properties**
   - Global theming system
   - Reusable values
   - Easy maintenance

2. **Modern Layouts**
   - Flexible grid system
   - Responsive components
   - Clean structure

3. **Animations & Transitions**
   - Smooth hover effects
   - State transitions
   - Professional polish

## 💡 Best Practices Learned

- Use of CSS custom properties for maintainability
- BEM-like naming conventions
- Responsive design patterns
- Performance considerations
- Animation best practices

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/your-username/holbertonschool-web_front_end.git
cd holbertonschool-web_front_end/CSS_advanced
```

2. Explore the styles:
   - Start with `styles/1-style.css`
   - Progress through numbered files
   - Each file builds on the previous one

## 📈 Learning Progress

<div class="mermaid">
xychart-beta
    title "Learning Curve"
    x-axis [Day 1, Day 5, Day 10, Day 15, Day 20]
    y-axis "Skill Level" 0 --> 100
    line ["10", "30", "55", "75", "95"]
</div>

## 🎓 Key Takeaways

1. **Modular CSS**
   - Breaking down styles into manageable chunks
   - Reusable components
   - Maintainable structure

2. **Advanced Techniques**
   - Custom properties
   - Complex selectors
   - Modern animations

3. **Professional Workflow**
   - Organized structure
   - Clear naming conventions
   - Progressive enhancement

## 🌈 Color Scheme

| Variable | Color | Usage |
|----------|--------|-------|
| `--color-primary` | ![#d73953](https://via.placeholder.com/15/d73953/000000?text=+) `#d73953` | Primary elements |
| `--color-black` | ![#090909](https://via.placeholder.com/15/090909/000000?text=+) `#090909` | Text & dark elements |
| `--color-white` | ![#ffffff](https://via.placeholder.com/15/ffffff/000000?text=+) `#ffffff` | Light elements |

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📜 License

This project is part of the Holberton School curriculum.

---

<p align="center">Made with ❤️ and a lot of CSS</p>
