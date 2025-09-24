# Baker T Pastry Shop Website

## Project Overview
A fully responsive, modern website for "Baker T" an artisan pastry shop specializing in French pastries and baked goods. Built using HTML5 and CSS3 with advanced styling techniques and animations.

## Live Demo
No live demo yet learning how to host on github soon 

## Features
- Three page responsive website
- 10+ CSS animations and transitions
- Custom bakery themed color scheme
- Custom order form with validation
- Fully accessible with semantic HTML

## File Structure
```
baker-t-website/
│
├── index.html          # Home page with featured pastries
├── menu.html           # Full bakery menu with 4 categories
├── about.html          # About page and custom order form
├── style.css           # Complete stylesheet with animations
├── README.md           # Project documentation
│
└── images/             # Image assets folder
│   ├── android-chrome-192x192.png
│   ├── android-chrome-512x512.png
│   ├── apple-touch-icon.png
│   ├── Ayaka-Tanaka-Headshot.png
│   ├── Ayaka-Tanaka.png
│   ├── baker.png
│   ├── bakery1.png
│   ├── Chocolate-Eclair.png
│   ├── Croissant.png
│   ├── favicon-16x16.png
│   ├── favicon-32x32.png
│   ├── favicon.ico
│   └── Strawberry-Tart.png
```
Windows (Alt Codes):
Hold Alt and type on the numeric keypad:

├ = Alt + 195
└ = Alt + 192
─ = Alt + 196
│ = Alt + 179

Mac:
Mac doesn't have direct shortcuts. Use:
Character Viewer: Press Cmd + Control + Space
Search for "box drawing"

## Advanced CSS Features Used

### 1. CSS Variables (Custom Properties)
Centralized theme management for consistent design:
```css
--primary-color: #d4a574;    /* Warm pastry brown */
--secondary-color: #2c1810;   /* Dark chocolate */
--accent-color: #f4e4d4;      /* Light cream */
--highlight-color: #c85a54;   /* Berry red */
```

### 2. CSS Animations (10+ Keyframe Animations)
- **`slideDown`** - Navigation bar entrance effect
- **`fadeIn`** - Hero section fade-in on load
- **`slideUp`** - Hero content entrance animation
- **`fadeInUp`** - Card entrance animations with stagger
- **`twinkle`** - Logo croissant decoration effect
- **`floatIcons`** - Background pastry icons floating
- **`bounce`** - Info card icon animation
- **`rotate`** - Menu section decorative elements
- **`slideInLeft/Right`** - About page section animations
- **`expandWidth`** - Section title underline animation
- **`successPulse`** - Form submission feedback

### 3. Pseudo-elements (::before & ::after)
Creative use of pseudo-elements for:
- Navigation link hover underlines
- Hero title decorative symbols
- Floating background emoji effects
- Card overlay effects on hover
- Menu item sliding highlight effect
- Footer decorative icons

### 4. Flexbox Layouts
Comprehensive flexbox implementation:
- **Navigation Bar** - Space between alignment with centered items
- **Hero Section** - Centered content with flexible spacing
- **Featured Cards** - Responsive card grid with wrap
- **Menu Items** - Two column layout with space between
- **Schedule Cards** - Flexible row arrangement
- **Contact Form** - Form rows with flexible columns
- **Info Sections** - Adaptive multicolumn layouts

### 5. CSS Transitions
Smooth transitions on all interactive elements:
- Hover effects (0.3s ease)
- Menu sliding animations
- Card scale transformations
- Button state changes
- Form focus states

## Design Choices

### Color Palette
The color scheme was carefully chosen to evoke a warm, inviting bakery atmosphere:
- **Primary (#d4a574)** - Warm pastry brown for main accents
- **Secondary (#2c1810)** - Rich chocolate brown for text and headers
- **Accent (#f4e4d4)** - Light cream for backgrounds
- **Highlight (#c85a54)** - Berry red for prices and CTAs

### Typography
- **Font Family**: Georgia serif - Classic, readable, elegant
- **Font Sizes**: Hierarchical scaling from 3.5rem to 0.95rem
- **Font Styles**: Italic for descriptions and quotes
- **Font Weight**: Bold for emphasis and prices

### Layout Strategy
1. **Sticky Navigation** - Always accessible menu bar
2. **Hero Sections** - Full viewport height for impact
3. **Card-Based Design** - Modular, scannable content
4. **Flexible Grids** - Responsive layouts using flexbox
5. **Mobile-First** - mobile first mindset will add mobile responsive later

## Responsive Design

### Breakpoints
- **Desktop**: > 768px (full layout)
 Will add these break points later 
- **Tablet/Mobile**: ≤ 768px (hamburger menu, stacked layout)
- **Small Mobile**: ≤ 480px (further optimizations)

### Mobile Features
- Hamburger menu with slide-in navigation
- Stacked card layouts
- Simplified animations
- Touch-friendly buttons and links
- Optimized font sizes

## Accessibility Features
- Semantic HTML5 elements (nav, main, section, article, footer)
- ARIA labels on all form elements
- Alt text for all images
- High contrast color ratios (WCAG AA compliant)
- Keyboard navigation support
- Focus states for interactive elements
- Logical heading hierarchy (h1 → h2 → h3)


## Installation & Usage

### Local Development
1. Clone or download the repository
2. No build process required - pure HTML/CSS
3. Open `index.html` in any modern browser

### Customization
1. Modify CSS variables in `:root` for quick theme changes
2. Update content in HTML files
3. Replace placeholder images in `/images` folder
4. Adjust animations in `@keyframes` sections

## Credits
- **Developer**: Bensky Sainvilus
- **Course**: Web Development I Assignment
- **Institution**: Broward college
- **Date**: September 8th 2025

## License
This project is created for educational purposes as part of a web development course assignment.

## Contact
For questions about this project:
- Email: sainb50@mail.broward.edu
- GitHub: OOS1
