# Himanshu Patidar - Portfolio

Personal portfolio website showcasing my work as a Spring Boot & Node.js backend developer.

🔗 **Live Site**: [https://sprintooo.github.io](https://sprintooo.github.io)

## About

This is my personal portfolio website highlighting my experience building backend systems, REST APIs, and microservices. The site features:

- **Experience**: Software Engineer at Inito, Software Developer Intern at Gigforce
- **Education**: B.S. in Mathematics and Statistics from IIT Kanpur
- **Projects**: E-commerce backend (BharatMart), Habit Manager API (Habitant), and AI/ML experiments
- **Skills**: Java, Spring Boot, Node.js, Express.js, PostgreSQL, Redis, RabbitMQ, Docker, Kubernetes, and more
- **Achievements**: Academic (JEE Advanced AIR 2426) and athletic accomplishments

## Tech Stack

The portfolio itself is built with:

- **HTML5** - Semantic markup with proper heading hierarchy
- **CSS3** - Custom properties (CSS variables), Grid, Flexbox, and modern features
- **Inter Font** - Google Fonts for improved typography
- **Responsive Design** - Mobile-first approach with 3 breakpoints (480px, 720px, 800px)
- **Accessibility** - Skip links, focus states, `prefers-reduced-motion`, `prefers-contrast`
- **SEO** - Meta tags, Open Graph, Twitter Card for social sharing

## Design System

The site uses a comprehensive CSS design system:

### Spacing Scale
```css
--space-xs: 4px    --space-sm: 8px    --space-md: 16px
--space-lg: 24px   --space-xl: 32px   --space-2xl: 48px   --space-3xl: 64px
```

### Shadow System
```css
--shadow-sm      /* Subtle depth */
--shadow-md      /* Card elevation */
--shadow-lg      /* Modal/dropdown */
--shadow-accent  /* Blue glow effect */
--shadow-glow    /* Bright accent glow */
```

### Color Palette
- **Primary Accent**: `#38bdf8` (Sky blue)
- **Secondary Accent**: `#a78bfa` (Purple)
- **Background**: Dark gradient with layered glows
- **Text**: `#f1f5f9` (bright) / `#94a3b8` (muted)

## Features

### Visual Design
- ✨ Glassmorphism cards with blur backdrop
- 🎨 Gradient name heading (white → blue → purple)
- 🌟 Layered background with subtle color glows
- 💫 Animated entrance effects (fade-in, stagger)
- 🔮 Hover glow effects on interactive elements

### User Experience
- 📱 Fully responsive with mobile-first approach
- 🖱️ Smooth scroll behavior
- 📌 Sticky navigation on desktop
- ⌨️ Full keyboard navigation support
- 🎯 44-48px touch targets on mobile

### Accessibility
- ♿ Custom `focus-visible` outlines
- 🔗 Skip to main content link
- 🎬 `prefers-reduced-motion` support
- 🔲 `prefers-contrast: high` support
- 📝 Proper semantic HTML structure

### Polish
- 🖨️ Print-friendly styles
- 📜 Custom styled scrollbars
- 👨‍💻 Emoji favicon
- ❤️ Animated heart in footer
- 🔗 Twitter Card & Open Graph tags

## Local Development

To run this site locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/sprintooo/sprintooo.github.io.git
   cd sprintooo.github.io
   ```

2. **Open in browser**
   ```bash
   # Option 1: Direct file open
   open index.html  # macOS
   xdg-open index.html  # Linux
   # or just double-click index.html in your file explorer

   # Option 2: Use a local server (recommended for testing)
   python3 -m http.server 8000
   # Then visit http://localhost:8000
   ```

3. **Make changes**
   - Edit `index.html` directly
   - Refresh browser to see changes
   - No build step required!

## Project Structure

```
.
├── index.html    # Main portfolio page (~1100 lines of HTML + CSS)
└── README.md     # This file
```

The entire site is contained in a single `index.html` file with inline CSS for simplicity and fast loading. No build tools, no dependencies, no JavaScript frameworks.

## CSS Architecture

The stylesheet is organized into clear sections:

```
1. CSS Variables (colors, spacing, typography, shadows)
2. Reset & Base styles
3. Layout (page, header, main grid)
4. Components (nav, sections, pills, lists, buttons)
5. Focus states & accessibility
6. Micro-animations & keyframes
7. Final polish (scrollbar, print, high contrast)
```

## Deployment

This site is automatically deployed via **GitHub Pages**:

- **Source**: `main` branch
- **URL**: https://sprintooo.github.io
- **Updates**: Automatic on push to `main`

Any changes merged to the `main` branch will be live within a few minutes.

## Browser Support

- ✅ Chrome/Edge (last 2 versions)
- ✅ Firefox (last 2 versions)
- ✅ Safari (last 2 versions)
- ✅ Mobile browsers (iOS Safari, Chrome for Android)

Features like `backdrop-filter` gracefully degrade in unsupported browsers.

## Contact

- **Email**: [himanshupatidar622@gmail.com](mailto:himanshupatidar622@gmail.com)
- **LinkedIn**: [himanshu-patidar-b609661a7](https://www.linkedin.com/in/himanshu-patidar-b609661a7)
- **GitHub**: [@sprintooo](https://github.com/sprintooo)

## License

This project is open source and available for personal use. Feel free to fork and customize for your own portfolio!

---

Built with ❤️ by Himanshu Patidar

