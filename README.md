# Announcement Bar - Noor

A powerful and feature-rich announcement bar solution for Shopify stores, offering seamless integration and extensive customization options. This announcement bar supports both marquee (continuous scroll) and single slide animations, making it perfect for displaying important messages, promotions, or announcements.

## Key Features

### Display Styles
- **Dual Display Modes**
  - Marquee Style (Continuous Scroll)
  - Single Slide Style
- **Text Alignment Options**
  - Left
  - Center
  - Right

### Animation Features
- **Marquee Mode**
  - Customizable scroll speed (0-80)
  - Bi-directional animation (Left-to-Right or Right-to-Left)
  - Pause on hover functionality
  - Hardware-accelerated animations for smooth performance
  - Transform3D and will-change properties for optimal rendering

- **Single Slide Mode**
  - Multiple animation effects:
    - Slide from bottom
    - Slide from top
    - Fade transition
    - Slide from left
    - Slide from right
  - Customizable slide duration (2-10 seconds)
  - Smooth transitions between slides

### Typography Customization
- **Font Control**
  - Custom font family selection via Shopify's font picker
  - Adjustable font size (12-60px for desktop, 10-40px for mobile)
  - Multiple font weight options:
    - Light (300)
    - Regular (400)
    - Medium (500)
    - Semi-Bold (600)
    - Bold (700)

- **Text Styling**
  - Text transformation options:
    - Normal
    - UPPERCASE
    - lowercase
    - Capitalize Each Word
  - Adjustable letter spacing (0-10px)
  - Customizable text spacing between announcements

### Responsive Design
- **Mobile-Optimized**
  - Separate mobile font size settings
  - Mobile-specific text spacing
  - Adaptive padding for different screen sizes
  - Touch-friendly interface

- **Spacing Control**
  - Independent padding settings for:
    - Desktop top/bottom padding
    - Mobile top/bottom padding
  - Customizable text spacing for both desktop and mobile

### Visual Customization
- **Color Management**
  - Custom text color selection
  - Background color customization
  - High contrast visibility options

### Content Management
- **Multiple Announcements**
  - Support for multiple text blocks
  - Optional link attachment to each announcement
  - Optional arrow indicator for linked announcements
  - Easy content management through Shopify admin

### Performance Optimization
- **Enhanced Performance**
  - CSS hardware acceleration
  - Optimized animation frames
  - Minimal DOM manipulation
  - Efficient event handling

## Technical Implementation

### CSS Features
```css
.custom-marquee {
  transform: translateZ(0);
  backface-visibility: hidden;
  perspective: 1000px;
  will-change: transform;
}
```
- Utilizes modern CSS properties for smooth animations
- Implements hardware acceleration for better performance
- Optimized for both desktop and mobile devices

### JavaScript Optimization
```javascript
document.addEventListener('DOMContentLoaded', function() {
  // Efficient slide management
  // Optimized animation timing
  // Smart event handling
});
```

## Installation Guide

1. **Theme Integration**
   - Add section through Shopify admin
   - No additional dependencies required
   - Seamless integration with existing theme

2. **Configuration**
   - Access through theme customizer
   - Real-time preview of changes
   - Easy-to-use interface

## Best Practices
- Mobile-first responsive design
- Performance-optimized animations
- Accessibility-compliant implementation
- SEO-friendly structure

## Copyright Notice
This code is protected under copyright law. Unauthorized use, modification, or distribution is strictly prohibited.

© 2025 Noor Ul Ahad - All rights reserved

## Support
For support or customization requests, please contact the author.

---
*Note: This announcement bar is designed to provide maximum flexibility while maintaining optimal performance across all devices and browsers.*
