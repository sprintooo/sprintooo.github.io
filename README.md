# Himanshu Patidar - Portfolio

Personal portfolio website showcasing my work as a Software Engineer specializing in backend development.

🔗 **Live Site**: [https://sprintooo.github.io](https://sprintooo.github.io)

## About

This is my personal portfolio website highlighting my experience building backend systems, REST APIs, and microservices. The site features:

- **Experience**: Software Engineer at Tekion, Inito, and Gigforce
- **Education**: B.S. in Mathematics and Statistics from IIT Kanpur
- **Projects**: E-commerce backend (BharatMart), Habit Manager API (Habitant), and AI/ML experiments
- **Skills**: Java, Spring Boot, Node.js, Express.js, PostgreSQL, Redis, RabbitMQ, Docker, Kubernetes, and more
- **Achievements**: Academic (JEE Advanced AIR 2426) and athletic accomplishments

## Tech Stack

The portfolio itself is built with:

- **HTML5** - Semantic markup with proper heading hierarchy
- **CSS3** - Custom properties (CSS variables), Grid, Flexbox, and modern features
- **Dual Font System** - Inter for body, JetBrains Mono for code/metadata
- **Responsive Design** - Mobile-first approach with optimized touch targets
- **Accessibility** - WCAG 2.1 AA compliant with full keyboard navigation
- **SEO** - Meta tags, Open Graph, Twitter Card for social sharing
- **JavaScript** - Scroll tracking, particle effects, custom cursor

## Design System

The site uses a comprehensive CSS design system:

### Spacing Scale
```css
--space-xs: 4px    --space-sm: 8px    --space-md: 16px
--space-lg: 24px   --space-xl: 32px   --space-2xl: 48px   --space-3xl: 64px
```

### Shadow System (Layered for Realistic Depth)
```css
--shadow-sm       /* Subtle card depth with inner highlight */
--shadow-md       /* Card elevation */
--shadow-lg       /* Modal/dropdown */
--shadow-elevated /* Floating elements with multi-layer depth */
--shadow-accent   /* Blue glow effect */
--shadow-glow     /* Bright accent glow */
--shadow-inset    /* Pressed/inset effects */
```

### Color Palette
- **Primary Accent**: `#38bdf8` (Sky blue)
- **Secondary Accent**: `#a78bfa` (Purple)
- **Tertiary Accent**: `#34d399` (Emerald green)
- **Background**: Dark gradient with layered glows + film grain texture
- **Text**: `#f8fafc` (bright) / `#9ca3af` (muted)

### Gradient Presets
```css
--gradient-accent: linear-gradient(135deg, var(--accent), var(--secondary));
--gradient-subtle: linear-gradient(135deg, rgba(56, 189, 248, 0.1), rgba(167, 139, 250, 0.1));
--gradient-glow: radial-gradient(circle, var(--accent-glow), transparent 70%);
```

### Typography
```css
--font-sans: 'Inter', system-ui, sans-serif;
--font-mono: 'JetBrains Mono', 'Fira Code', monospace;
```

## Features

### Visual Design
- ✨ Glassmorphism cards with blur backdrop and layered shadows
- 🎨 Gradient text headings (accent → secondary)
- 🌟 Layered background with subtle color glows + film grain texture
- 💫 Animated entrance effects (fade-in, stagger)
- 🔮 Hover glow effects with brand-colored shadows
- 🎭 3D card depth with inner light/dark edges
- 📐 Decorative section dividers and gradient underlines

### User Experience
- 📱 Fully responsive with optimized mobile experience
- 🖱️ Custom animated cursor (desktop only)
- 📍 Active navigation tracking with scroll position
- 🎯 48px minimum touch targets on mobile
- 🌊 Particle background animation
- ⚡ Dual-ring loading spinner with gradient
- 📊 Scroll progress bar with glow effect

### Micro-interactions
- ✨ Title underline animation on hover
- 💜 Brand-colored social link shadows (LinkedIn blue, GitHub purple, Email red)
- ❤️ Pulsing heart with glow on hover
- 🏷️ Pill badges with gradient hover effect
- 📝 List item gradient text shift on hover

### Accessibility
- ♿ WCAG 2.1 Level AA compliant touch targets
- 🔗 Skip to main content link
- 🎬 `prefers-reduced-motion` support
- 🔲 `prefers-contrast: high` support
- 🌓 `prefers-reduced-transparency` support
- 🖥️ Windows High Contrast mode support
- ⌨️ Full keyboard navigation with visible focus states

### Print & Performance
- 🖨️ Print-optimized styles with URL display after links
- 📜 Custom styled scrollbars
- 👨‍💻 Emoji favicon
- 🔗 Twitter Card & Open Graph tags
- 📴 Disabled hover effects on touch devices

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
├── index.html    # Main portfolio page (~3200 lines of HTML + CSS + JS)
└── README.md     # This file
```

The entire site is contained in a single `index.html` file with inline CSS and JavaScript for simplicity and fast loading. No build tools, no npm dependencies, no frameworks.

## Architecture

The code is organized into clear sections:

### CSS Sections
```
1. CSS Variables (colors, spacing, typography, shadows, gradients)
2. Reset & Base styles
3. Layout (page, header, main grid with column divider)
4. Components (nav, sections, pills, lists, contact links)
5. Focus states & accessibility (focus-visible, skip-link)
6. Micro-animations & keyframes (heartbeat, skeleton, shimmer)
7. Custom cursor & spotlight effect
8. Print styles & media queries
9. High contrast & reduced motion support
```

### JavaScript Sections
```
1. Page loader with dual-ring spinner
2. Scroll progress bar
3. Active navigation tracking
4. Particle background system
5. Custom cursor with trailing effect
6. Spotlight mouse follower
7. Text split animation for name
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

## Recent Updates (v2.0)

This portfolio was recently enhanced through 10 design iterations:

| Iteration | Focus | Highlights |
|-----------|-------|------------|
| 1 | Typography | JetBrains Mono, font variables, company highlighting |
| 2 | Section Dividers | Gradient underlines, column divider, dot separators |
| 3 | Card Depth | Layered shadows, 3D effects, elevated hover states |
| 4 | Navigation | Active tracking, scroll progress glow |
| 5 | Micro-interactions | Title underlines, brand shadows, heart glow |
| 6 | Mobile | Smaller pills, stacked links, touch optimization |
| 7 | Color System | Tertiary color, gradient presets, gradient text |
| 8 | Loading | Dual-ring spinner, enhanced skeleton shimmer |
| 9 | Visual Polish | Film grain texture, header glow line |
| 10 | Accessibility | 48px touch targets, enhanced print styles |

## License

This project is open source and available for personal use. Feel free to fork and customize for your own portfolio!

---

Built with ❤️ by Himanshu Patidar
