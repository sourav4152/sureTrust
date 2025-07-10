# Extraordinary Crepe House Website

A modern, responsive single-page website for a crepe house/restaurant, built with HTML, CSS, and minimal JavaScript.

## Features

### ✨ Design Features
- **Modern & Clean Design**: Elegant typography and spacing with a warm color palette
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Hover effects, transitions, and micro-interactions
- **Professional Layout**: Well-structured sections with proper visual hierarchy

### 📱 Responsive Design
- Mobile-first approach
- Collapsible navigation menu for mobile
- Responsive grid layouts
- Optimized typography scaling
- Touch-friendly interactive elements

### 🎨 Interactive Elements
- **Navigation**: Hover effects with underline animations
- **Buttons**: Lift effects on hover with shadow animations  
- **Cards**: Subtle lift and shadow effects on hover
- **Menu Items**: Image zoom effects and card animations
- **Tab System**: Smooth transitions between menu categories

### 📋 Sections Included
1. **Navigation Header**: Fixed header with smooth scroll navigation
2. **Hero Section**: Eye-catching banner with call-to-action
3. **About Section**: Story and feature highlights with icon cards
4. **Menu Section**: Tabbed interface (Sweet, Savory, Beverages)
5. **Experience Section**: Hours, contact info, and newsletter signup
6. **Footer**: Simple navigation and copyright

## File Structure

```
/
├── index.html          # Main HTML structure
├── style.css           # Complete CSS styling
├── script.js           # Minimal JavaScript functionality
└── README.md           # This documentation
```

## Setup Instructions

1. **Download/Clone the files** to your project directory
2. **Add your images** to the empty `src=""` attributes in the HTML
3. **Customize content** as needed (text, colors, menu items)
4. **Open index.html** in a web browser to view the site

## Adding Images

The website is designed with placeholder image sources. Replace the empty `src=""` attributes with your image paths:

### Hero Section
- `.hero-img`: Main hero banner image (recommended: 500x400px)

### Feature Icons  
- `.feature-icon img`: Small icons for the 4 feature cards (recommended: 30x30px)

### Menu Items
- `.menu-image img`: Food photos for each menu item (recommended: 300x200px)

### Suggested Image Types
- **Hero**: High-quality crepe preparation or restaurant interior
- **Menu Items**: Professional food photography of each crepe
- **Icons**: Simple line icons for Made Fresh, Home Grown, etc.

## Customization

### Colors
The website uses a warm, restaurant-friendly color palette:
- **Primary**: `#d4a574` (Golden brown)
- **Dark**: `#2c2c2c` (Charcoal)
- **Light**: `#f8f6f0` (Cream)
- **Background**: `#ffffff` (White)

To change colors, update the CSS variables or find-replace the hex codes in `style.css`.

### Content
- **Restaurant Name**: Update "Crepe House" in the logo and title
- **Menu Items**: Add/remove items in the HTML structure
- **Contact Info**: Update phone, email, and address in the Experience section
- **Hours**: Modify operating hours as needed

### Layout
- **Container Width**: Maximum 1200px (adjustable in `.container`)
- **Section Padding**: 80px top/bottom (adjustable in `section`)
- **Grid Layouts**: Auto-responsive based on content

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)  
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## Performance Features

- **Optimized CSS**: Efficient selectors and minimal redundancy
- **Smooth Scrolling**: CSS-based smooth scrolling behavior
- **Lightweight**: Minimal JavaScript for core functionality only
- **Fast Loading**: Clean HTML structure and optimized styling

## JavaScript Functionality

The minimal JavaScript handles:
- Menu tab switching between Sweet/Savory/Beverages
- Mobile navigation toggle
- Smooth scrolling for navigation links

*Note: If you prefer a completely JavaScript-free version, you can remove the script.js file, though the menu tabs will need manual CSS modifications to work properly.*

## License

This is a custom-built template. Feel free to modify and use for your restaurant/business needs.

## Support

For questions about customization or implementation, refer to the well-commented CSS and HTML code structure.