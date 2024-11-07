# Advanced CSS Styling Project 🎨

> A comprehensive project to master advanced CSS concepts and modern styling techniques.

## 🎯 Project Overview

This project explores advanced CSS concepts through a series of progressive tasks, from basic styling to complex animations. We'll build a modern, responsive website while learning essential CSS techniques.

## 🗂️ Project Structure

```
holbertonschool-web_front_end/
└── CSS_advanced/
    ├── images/
    │   ├── pic-about-01.jpg
    │   ├── pic-article-01.jpg
    │   ├── pic-article-02.jpg
    │   ├── pic-article-03.jpg
    │   ├── pic-person-01.jpg
    │   ├── pic-person-02.jpg
    │   ├── pic-person-03.jpg
    │   ├── pic-work-01.jpg
    │   ├── pic-work-02.jpg
    │   └── pic-work-03.jpg
    └── styles/
        ├── 1-style.css  # Basic scroll behavior
        ├── 2-style.css  # Color values
        └── ... up to 32-style.css
```

## 📚 Tasks Breakdown

### Foundation Tasks (1-5)
- Custom scroll behavior implementation
- Color variables setup
- Font families configuration
- Base size settings
- Weight variations

### Styling Tasks (6-10)
- Google Fonts integration
- Line heights configuration
- Links decoration
- Section alignments
- Header styling

### Component Tasks (11-15)
- Tagline styling
- Headings configuration
- Pseudo-classes implementation
- Normalize CSS integration
- Universal box-sizing

### Layout Tasks (16-20)
- Container setup
- Section padding
- Navigation styling
- Grid system
- Float clearing

### Advanced Tasks (21-25)
- Simplified selectors
- Dark theme
- SVG icons
- Background effects
- Button styling

### Polish Tasks (26-32)
- Border radius implementation
- Hero section
- Header fixes
- Navigation effects
- Work grid
- Testimonials
- Transitions and animations

## 🌟 Key Features

### Custom Properties System
```css
:root {
    --color-primary: #d73953;
    --text-color: #161616;
    --font-family-base: "Open Sans", "Helvetica Neue", Helvetica, Arial, sans-serif;
    --font-family-title: "Raleway", "Helvetica Neue", Helvetica, Arial, sans-serif;
}
```

### Grid System
```css
.row {
    display: flex;
    flex-wrap: wrap;
}

[class^="col-"] {
    padding: 0.5rem;
}

.col-1-3 {
    width: 33.33%;
}

.col-1-2 {
    width: 50%;
}
```

### Theme Implementation
```css
[data-section-theme="dark"] {
    --text-color: var(--color-white);
    --section-title-color: var(--color-white);
    background: var(--color-black);
}
```

## 🎓 Learning Objectives

1. **CSS Custom Properties**
   - Global theming
   - Variable scoping
   - Dynamic value updates

2. **Responsive Design**
   - Grid systems
   - Flexible layouts
   - Mobile-first approach

3. **Animation & Transitions**
   - Smooth state changes
   - Interactive elements
   - Performance optimization

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/[your-username]/holbertonschool-web_front_end.git
```

2. Navigate to the project:
```bash
cd holbertonschool-web_front_end/CSS_advanced
```

3. Follow the tasks progression through the numbered CSS files.

## 📈 Skills Developed

- Advanced CSS selector usage
- Custom properties management
- Responsive design techniques
- Animation implementation
- Modern CSS best practices
- Cross-browser compatibility
- Performance optimization
- Code organization

## 🌈 Color Scheme Reference

| Variable Name | Hex Code | Usage |
|--------------|----------|--------|
| Primary | `#d73953` | Main accent color |
| Black | `#090909` | Text & dark elements |
| White | `#ffffff` | Light elements |
| Light Grey | `#f3f3f3` | Backgrounds |
| Dark Grey | `#353535` | Secondary elements |

## 💡 Best Practices Learned

1. **Organization**
   - Modular CSS structure
   - Consistent naming conventions
   - Logical file organization

2. **Maintainability**
   - Use of CSS variables
   - Reusable components
   - Clear documentation

3. **Performance**
   - Optimized selectors
   - Efficient animations
   - Browser compatibility

## 🤝 Contributing

Feel free to:
- Submit issues
- Propose improvements
- Share feedback
- Ask questions

## 📜 License

This project is part of the Holberton School curriculum.

---

<p align="center">Made with ❤️ and CSS magic ✨</p>
