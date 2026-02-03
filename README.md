# Coffee World - Responsive Layout with Tailwind CSS

A fully responsive website about coffee, coffee brewing methods, and coffee equipment, built using Tailwind CSS.

## 🎯 Project Overview

This project demonstrates a modern, adaptive layout that transforms from a three-column grid to two columns and finally to a single column based on screen width. The website showcases coffee culture, brewing methods, and equipment with interactive components built using pure CSS.

## ✨ Features

### 1. **Responsive Grid Layout**
- **Desktop (xl)**: 3-column layout
- **Tablet (md)**: 2-column layout
- **Mobile**: Single column layout
- Adaptive column reordering for optimal mobile experience

### 2. **Column Proportions**
- **Left**: 3 parts (xl:col-span-3) - Image slider
- **Main**: 6 parts (xl:col-span-6) - Main content (widest)
- **Right**: 3 parts (xl:col-span-3) - Survey form

### 3. **Header with Two-Level Menu**
- Navigation menu with dropdown submenus
- Pure CSS implementation using `:hover` pseudo-class
- No JavaScript required
- Fully responsive with flex-wrap

### 4. **Image Slider (LEFT Column)**
- 5 vertical images of coffee equipment
- CSS-only slider using `scroll-snap`
- Smooth scrolling behavior
- Visual indicators
- Images include: Turkish coffee pot (Cezve), French press, Espresso machine, Moka pot, Chemex

### 5. **Accordion Component (MAIN Column)**
- 5 expandable sections with coffee information
- Built with HTML `<details>` and `<summary>` elements
- Animated transitions
- Topics covered:
  - History of coffee brewing
  - Main coffee varieties (Arabica, Robusta)
  - Coffee preparation methods
  - Chemical composition and health benefits
  - Latte art techniques

### 6. **Survey Form (RIGHT Column)**
- Multiple input types:
  - Text input (name)
  - Email input
  - Radio buttons (coffee variety preference)
  - Select dropdown (roast level)
  - Checkboxes (brewing methods)
  - Number input (daily consumption)
  - Textarea (comments)
- Submit and Reset buttons
- Styled with Tailwind utility classes

### 7. **Footer**
- Contact information
- Quick links
- Social media icons
- Copyright notice
- Three-column responsive layout

## 🎨 Design Features

- **Color Scheme**: Amber/brown tones reflecting coffee theme
- **Gradients**: Used in header and footer for visual appeal
- **Shadows**: Box shadows for depth and card-like appearance
- **Rounded Corners**: Modern, friendly design
- **Hover Effects**: Interactive feedback on buttons and links
- **Responsive Typography**: Scales appropriately across devices

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **CSS3**: Custom styles for slider and dropdown functionality

## 📱 Responsive Breakpoints

- **Mobile**: < 768px (1 column)
- **Tablet**: 768px - 1279px (2 columns)
- **Desktop**: ≥ 1280px (3 columns)

## 🚀 Getting Started

1. Clone or download the repository
2. Open `index.html` in a modern web browser
3. No build process or dependencies required!

## 📂 Project Structure

```
HillelFullStack-Tailwind-Adaptive/
├── index.html          # Main HTML file
├── img/                # Image directory (optional)
│   ├── jezva.jpg
│   ├── press.jpg
│   ├── express.jpg
│   ├── moka.jpg
│   └── kemeks.jpg
└── README.md           # This file
```

## 🎓 Educational Purpose

This project was created as a learning exercise to demonstrate:
- Responsive web design principles
- Tailwind CSS utility classes
- CSS Grid and Flexbox layouts
- Pure CSS interactive components
- Semantic HTML structure
- Accessibility considerations

## 🌐 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 Key Implementation Details

### CSS-Only Slider
Uses `scroll-snap-type` and `scroll-snap-align` for smooth, native scrolling behavior without JavaScript.

### CSS-Only Accordion
Leverages HTML5 `<details>` and `<summary>` elements for expandable/collapsible sections.

### CSS-Only Dropdown Menu
Implements hover-based dropdown using `.dropdown:hover .dropdown-menu` selector.

## 🎯 Learning Outcomes

- Understanding of responsive grid systems
- Mastery of Tailwind CSS utility classes
- Implementation of interactive components without JavaScript
- Mobile-first design approach
- Semantic HTML best practices

## 📄 License

This project is open source and available for educational purposes.

## 👨‍💻 Author

Created as part of Hillel Full Stack course - Tailwind CSS Adaptive Layout assignment.

---

**Note**: This project uses Tailwind CSS via CDN for simplicity. For production use, consider using a build process with PostCSS for optimization and purging unused styles.
