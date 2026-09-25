# Reeh Flex - Streetwear E-commerce Website

**Student:** Rorisang Malebadi  
**Student ID:** ST10540065  
**Course:** Web Development (WEDE50)  
**Date:** 2026  

## Project Overview

Reeh Flex is a South African streetwear brand website showcasing bold graphics, oversized fits, and a strong focus on self-expression. This project is a responsive, multi-page e-commerce website developed as part of the Web Development course.

## Project Structure

```
reeh-flex/
├── index.html
├── products.html
├── about.html
├── contact.html
├── enquiry.html
├── style.css
├── images/
│   ├── logo.jpg
│   ├── hero.jpg
│   ├── about.jpg
│   ├── product1.jpg
│   ├── product2.jpg
│   ├── product3.jpg
│   ├── product4.jpg
│   ├── product5.jpg
│   └── product6.jpg
└── README.md
```

## Part 1: HTML Structure (Completed)

### Pages Developed:
- **Home Page (index.html)** - Hero section with featured products and brand story
- **Products Page (products.html)** - Product catalog organized by capsule collections
- **About Page (about.html)** - Company history, mission, vision, and target audience
- **Contact Page (contact.html)** - Contact information, location map, and contact form
- **Enquiry Page (enquiry.html)** - Product enquiry and sponsorship form

### Part 1 Feedback:
- Grade: 61/100
- Feedback: Repository was private, unable to mark
- Status: Repository access has been resolved

---

## Part 2: CSS Styling and Responsive Design

### Learning Outcomes Achieved:

✅ **External CSS Stylesheet**
- Created `style.css` as external stylesheet linked to all HTML pages
- Consistent naming convention: `style.css`

✅ **Typography Styling**
- Font families: Segoe UI for body text, Arial for headings
- Font sizes: h1 (2rem), h2 (1.75rem), h3 (1.35rem), h4 (1.1rem), p (1rem)
- Font weights: 600-700 for headings, 400-500 for body
- Line height: 1.6-1.8 for optimal readability
- Letter spacing: Applied to headings (0.01em - 0.05em) for visual hierarchy

✅ **Layout Structure**
- CSS Grid for product sections (auto-fit, minmax layout)
- Flexbox for header and navigation
- Max-width container (1200px) for desktop experience
- Proper spacing and padding throughout

✅ **Visual Styling**
- Color scheme: Black (#000), White (#fff), Dark gray (#333), Light gray (#f5f5f5)
- Backgrounds: Gradient for hero section, solid colors for sections
- Borders: 1-2px solid borders on key elements
- Box shadows: 2-16px shadows for depth (0.08-0.15 opacity)
- Border radius: 4-8px for modern rounded corners
- Hover effects: Color changes, transforms, shadow enhancements
- Focus states: 2px solid #ff6b35 outline for accessibility

✅ **Responsive Design Implementation**

#### Three Breakpoints:

1. **Desktop (1200px+)**
   - Full multi-column layouts
   - Maximum content width: 1200px
   - Optimal spacing and font sizes
   - Grid layouts with 3+ columns for products

2. **Tablet (768px - 1199px)**
   - Adjusted font sizes (1.5rem headings)
   - Navigation changes to flexible wrapping
   - Product grid: 2-3 columns
   - Reduced padding and margins
   - Image heights: 200-250px

3. **Mobile (480px - 767px)**
   - Single column layouts
   - Base font size: 14px
   - Navigation: Stacked layout
   - Product grid: 1 column
   - Full-width forms
   - Reduced padding: 0.5-0.75rem
   - Image heights: 180px
   - Button: Full width on mobile

#### Responsive Features:
- Meta viewport tag: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
- Relative units: rem, em, % for font sizes and spacing
- CSS Grid with auto-fit and minmax for flexible layouts
- Media queries with mobile-first approach
- Responsive images: max-width 100%, height auto
- Responsive forms: Full-width inputs on mobile
- Responsive iframe: max-width 100%

✅ **CSS Cascading & Selectors**
- Efficient selector usage with minimal classes
- Cascading nature leveraged for typography hierarchy
- Pseudo-classes: `:hover`, `:focus`, `:active` for interactivity
- Attribute selectors for form elements
- Nth-of-type selectors for section-specific styling

✅ **Form Styling**
- Input fields, textareas, selects with consistent styling
- Focus states with border color and box-shadow
- Button styling with hover and active states
- Responsive form widths and font sizes
- Accessible form labels with proper spacing

✅ **Interactive Elements**
- Navigation links with hover effects (background color change)
- Product cards with elevation on hover (transform: translateY(-4px))
- Buttons with color transition and scale effects
- Links with color and text-decoration transitions
- All transitions: 0.3s ease for smooth animations

✅ **Browser Compatibility**
- CSS Reset for consistent baseline
- Flexbox and Grid support (modern browsers)
- Transition and transform support
- CSS custom properties ready (future enhancement)

---

## Changelog

### Part 2 - CSS Styling and Responsive Design (2026-01-19)

#### Added:
- **style.css** - Complete external stylesheet (580+ lines)
  - CSS Reset and base styles
  - Typography styling with hierarchy
  - Header, navigation, and footer styling
  - Product grid layouts with CSS Grid
  - Hero section with gradient background
  - Form styling for contact and enquiry pages
  - Responsive design with 3 breakpoints
  - Accessibility focus states
  - Interactive element animations

- **Updated HTML Files:**
  - `index.html` - Added stylesheet link in head
  - `products.html` - Added stylesheet link in head
  - `about.html` - Added stylesheet link in head
  - `contact.html` - Added stylesheet link in head
  - `enquiry.html` - Added stylesheet link in head

#### Improvements from Part 1 Feedback:
- Repository access issue resolved
- All files properly structured and linked
- Professional external stylesheet implementation
- Consistent styling across all pages

#### CSS Architecture Highlights:
- Modular sections (Reset, Typography, Layout, Responsive, Forms)
- Clear commenting for maintainability
- Mobile-first responsive approach
- Accessibility considerations throughout
- Semantic HTML styling without excessive classes

#### Testing:
- Tested on desktop (1200px+)
- Tested on tablet (768px - 1199px)
- Tested on mobile (480px - 767px)
- Cross-browser compatibility verified
- Form inputs tested for focus states
- Navigation tested for responsiveness
- Product grids tested for layout flexibility

---

## References

1. **MDN Web Docs**
   - CSS Flexbox: https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox
   - CSS Grid: https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Grids
   - Responsive Design: https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design

2. **CSS Tricks**
   - A Complete Guide to Grid: https://css-tricks.com/snippets/css/complete-guide-grid/
   - A Complete Guide to Flexbox: https://css-tricks.com/snippets/css/a-guide-to-flexbox/

3. **W3C Standards**
   - CSS Cascading and Inheritance: https://www.w3.org/TR/css-cascade-3/
   - Media Queries: https://www.w3.org/TR/css3-mediaqueries/

4. **Web Accessibility**
   - WCAG 2.1 Guidelines: https://www.w3.org/WAI/WCAG21/quickref/
   - Focus Visible: https://www.w3.org/WAI/WCAG21/Understanding/focus-visible

---

## Git Commit Information

```
Commit: Part 2 - CSS Styling and Responsive Design
Date: 2026-01-19
Author: Rorisang Malebadi (ST10540065)
Message: Implement external stylesheet with responsive design for desktop, tablet, and mobile devices
```

### Files Changed:
- Created: `style.css`
- Modified: `index.html`, `products.html`, `about.html`, `contact.html`, `enquiry.html`
- Created: `README.md`

---

## Submission Requirements - Part 2

✅ **HTML Files Submitted** - All 5 pages with stylesheet links  
✅ **External Stylesheet** - `style.css` (580+ lines, well-organized)  
✅ **Responsive Design** - 3 breakpoints (desktop, tablet, mobile)  
✅ **Typography Styling** - Complete hierarchy with font properties  
✅ **Layout Structure** - CSS Grid and Flexbox implementation  
✅ **Visual Styling** - Colors, borders, shadows, and effects  
✅ **Interactive Elements** - Hover, focus, and active states  
✅ **README Updated** - Changelog with Part 2 details  
✅ **GitHub Repository** - All files committed and pushed  
✅ **Screenshot Evidence** - Different screen sizes included in submission

---

## How to Use

1. Clone the repository
2. Ensure all image files are in the `images/` folder
3. Open `index.html` in a web browser
4. Navigate through pages using the navigation menu
5. Test responsive design by resizing browser window or using device emulation

---

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

---

**End of README**
