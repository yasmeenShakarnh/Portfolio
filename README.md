# Yasmeen's Web Development Portfolio

A responsive, accessible portfolio website built with HTML, SCSS, and JavaScript following BEM methodology and modern web development best practices.

## 🚀 Features

### Design & Layout
- **Responsive Design**: Adapts seamlessly to desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Wireframe Compliance**: Layout matches provided design specifications

### Technical Features
- **SCSS Preprocessor**: Organized with variables, mixins, and nested selectors
- **BEM Methodology**: Consistent and maintainable CSS class naming
- **Advanced CSS Properties**: Uses `min()` function for responsive layouts
- **Smooth Animations**: Header shrink on scroll and section fade-in effects
- **Accessibility**: WCAG AA compliant with semantic HTML and ARIA labels

### Interactive Elements
- **Header Shrink**: Navigation bar minimizes height when scrolling
- **On-Scroll Effects**: Sections animate into view as they enter the viewport
- **Hover Transitions**: Smooth color and transform transitions on interactive elements
- **Reduced Motion Support**: Respects user preferences for reduced motion

## 📁 Project Structure

```
yasmeen-shkarnah/
├── dist/
│   └── main.css              # Compiled CSS file
├── src/
│   ├── index.html            # Main HTML file
│   ├── img/
│   │   ├── profile.jpg       # Profile image
│   │   ├── project1.jpg      # Project screenshot 1
│   │   ├── project2.jpg      # Project screenshot 2
│   │   └── project3.jpg      # Project screenshot 3
│   ├── js/
│   │   └── scrollAnimation.js # JavaScript for scroll effects
│   └── scss/
│       ├── main.scss         # Main SCSS file (imports all partials)
│       ├── base/
│       │   ├── base.scss     # Base styles and typography
│       │   └── resets.scss   # CSS resets and variables
│       ├── blocks/
│       │   ├── blocks.scss   # Imports all block components
│       │   ├── header.scss   # Navigation header styles
│       │   ├── intro-banner.scss # Hero section styles
│       │   ├── projects.scss # Projects section styles
│       │   ├── skills.scss   # Skills section styles
│       │   ├── resume.scss   # Resume section styles
│       │   ├── contact.scss  # Contact section styles
│       │   └── footer.scss   # Footer styles
│       └── utils/
│           ├── utils.scss    # Aggregates variables and mixins
│           ├── variables.scss # SCSS variables (colors, fonts, breakpoints)
│           └── mixins.scss   # Reusable SCSS mixins
├── package.json              # Project dependencies
└── README.md                 # This file
```

## 🛠️ Setup Instructions

### Prerequisites
- Node.js (for SCSS compilation)
- A modern web browser

### Installation
1. **Clone or download** the project files
2. **Install dependencies** (if using npm):
   ```bash
   npm install
   ```

### Development
1. **Compile SCSS** to CSS:
   ```bash
   npx sass src/scss/main.scss dist/main.css --no-source-map
   ```

2. **Open the website**:
   - Open `src/index.html` directly in your browser
   - Or use a local server (recommended):
     - VS Code: Install "Live Server" extension and right-click `index.html`
     - Or use any local development server

### File Paths
- **For direct file opening**: Use `src/index.html`
- **For local server**: Serve from project root and open `src/index.html`

## 🎨 Design System

### Colors
- **Primary**: `#0044cc` (Blue)
- **Secondary**: `#f5f5f5` (Light Gray)
- **Text**: `#222` (Dark Gray)
- **Background**: `#f7f8fa` (Light Background)

### Typography
- **Font Family**: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
- **Headings**: Bold (700 weight)
- **Body Text**: Regular weight with 1.6 line height

### Breakpoints
- **Mobile**: `max-width: 480px`
- **Tablet**: `max-width: 768px`
- **Desktop**: Above 768px

## ♿ Accessibility Features

- **Semantic HTML**: Proper use of `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`
- **ARIA Labels**: Descriptive labels for navigation and interactive elements
- **Alt Text**: Meaningful descriptions for all images
- **Keyboard Navigation**: All interactive elements are keyboard accessible
- **Focus Indicators**: Visible focus states for all clickable elements
- **Color Contrast**: Meets WCAG AA standards (4.5:1 ratio)
- **Reduced Motion**: Respects `prefers-reduced-motion` user preference

## 📱 Responsive Features

### Header
- **Desktop**: Full navigation with logo and menu items
- **Mobile**: Stacked layout with reduced font sizes
- **Scroll Effect**: Header shrinks on scroll with smooth transitions

### Intro Banner
- **Desktop**: Side-by-side layout (image and text)
- **Mobile**: Stacked layout (image above text)
- **Background**: Responsive background image

### Projects Section
- **Desktop**: Three-column grid layout
- **Mobile**: Single-column stacked layout
- **Cards**: Equal height with hover effects

### Contact Section
- **Desktop**: Horizontal layout for contact methods
- **Mobile**: Vertical stacked layout
- **Icons**: SVG icons with proper ARIA labels

## 🔧 Technical Implementation

### SCSS Architecture
- **Aggregated Approach**: `utils/utils.scss` consolidates variables and mixins
- **BEM Naming**: `.block__element--modifier` convention
- **Nesting**: Proper SCSS nesting for maintainable code
- **Variables**: Centralized color, font, and spacing variables
- **Mixins**: Reusable patterns for responsive design and transitions

### JavaScript Features
- **Intersection Observer**: Efficient scroll-based animations
- **Event Listeners**: Smooth header shrink on scroll
- **Performance**: Optimized for smooth 60fps animations

### CSS Features
- **CSS Grid & Flexbox**: Modern layout techniques
- **CSS Custom Properties**: Responsive design with `min()` function
- **Transitions**: Smooth 0.3s transitions for all interactive elements
- **Media Queries**: Mobile-first responsive design

## 📋 Assignment Requirements Met

### ✅ Basic Requirements
- [x] Follow wireframes to build project layout
- [x] Create responsive design for all screen sizes
- [x] No layout overflow or breaking elements

### ✅ Methodology
- [x] BEM methodology with clear file structure
- [x] Organized SCSS folders (base, blocks, utils)
- [x] Logical class names reflecting component purpose
- [x] Aggregated approach for utilities

### ✅ Preprocessors
- [x] Compiled SCSS into main.css
- [x] Variables for colors, fonts, and spacing
- [x] Mixins for responsive design and transitions
- [x] Proper nesting for BEM selectors

### ✅ CSS Techniques
- [x] Advanced CSS property (`min()` function)
- [x] Button hover transitions
- [x] Section fade-in animations
- [x] Smooth, non-distracting effects

### ✅ Responsive Animations
- [x] Header minimizes height on scroll
- [x] On-scroll effects for sections
- [x] Reduced motion media query support

### ✅ Accessibility
- [x] Semantic HTML structure
- [x] Proper heading hierarchy
- [x] Alt attributes for images
- [x] ARIA labels for interactive elements
- [x] Keyboard accessibility
- [x] Color contrast compliance

## 🚀 How to Use

1. **View the Portfolio**: Open `src/index.html` in your browser
2. **Navigate Sections**: Use the header navigation or scroll through sections
3. **Experience Animations**: Scroll to see header shrink and section fade-in effects
4. **Test Responsiveness**: Resize your browser window to see mobile/tablet layouts
5. **Check Accessibility**: Use keyboard navigation (Tab key) and screen readers

