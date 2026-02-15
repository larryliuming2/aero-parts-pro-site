# Aero Parts Pro - Website Specification

## 1. Project Overview

- **Project Name**: Aero Parts Pro
- **Type**: Single-page marketing website
- **Core Functionality**: Showcase high-performance automotive aerodynamic components (wings, splitters, diffusers) with product gallery and contact form
- **Target Users**: Car enthusiasts, automotive performance shops, racing teams

---

## 2. UI/UX Specification

### Layout Structure

**Sections (top to bottom):**
1. **Navigation Bar** - Fixed top, logo + nav links
2. **Hero Section** - Full viewport height, bold headline + CTA
3. **Products Section** - Grid gallery of aerodynamic components
4. **Features Section** - Why choose us benefits
5. **Contact Section** - Contact form
6. **Footer** - Copyright + social links

**Responsive Breakpoints:**
- Mobile: < 768px (single column, stacked layout)
- Tablet: 768px - 1024px (2-column grid)
- Desktop: > 1024px (3-column grid, full layout)

### Visual Design

**Color Palette:**
- Background Primary: `#0a0a0a` (near black)
- Background Secondary: `#141414` (dark gray)
- Background Tertiary: `#1a1a1a` (card backgrounds)
- Accent Primary: `#ff4d00` (racing orange)
- Accent Secondary: `#ff6b2c` (lighter orange)
- Text Primary: `#ffffff` (white)
- Text Secondary: `#a0a0a0` (muted gray)
- Border Color: `#2a2a2a` (subtle borders)

**Typography:**
- Headings: "Orbitron", sans-serif (futuristic, automotive feel)
- Body: "Rajdhani", sans-serif (modern, clean)
- Font Sizes:
  - H1: 3.5rem (mobile: 2rem)
  - H2: 2.5rem (mobile: 1.75rem)
  - H3: 1.5rem (mobile: 1.25rem)
  - Body: 1rem
  - Small: 0.875rem

**Spacing System:**
- Section padding: 100px vertical (mobile: 60px)
- Container max-width: 1200px
- Card gap: 30px (mobile: 20px)
- Element spacing: 8px base unit

**Visual Effects:**
- Cards: subtle border glow on hover (`box-shadow: 0 0 20px rgba(255, 77, 0, 0.3)`)
- Buttons: gradient background with scale transform on hover
- Hero: diagonal split with geometric pattern overlay
- Smooth scroll behavior
- Fade-in animations on scroll

### Components

**Navigation:**
- Logo (text-based "AERO PARTS PRO")
- Nav links: Products, Features, Contact
- Mobile: hamburger menu with slide-in drawer
- Background becomes solid on scroll

**Hero Section:**
- Large headline: "PRECISION AERODYNAMICS"
- Subheadline: "Dominate the track with premium aerodynamic components"
- Two CTA buttons: "Explore Products" (primary), "Contact Us" (outline)
- Background: dark with geometric angular patterns

**Product Cards:**
- Image placeholder (gradient with icon)
- Product name
- Category tag (Wing/Splitter/Diffuser)
- Brief description
- "Learn More" link
- Hover: lift effect + orange glow

**Contact Form:**
- Fields: Name, Email, Phone, Message
- Submit button with loading state
- Form validation with error messages
- Success message on submit

---

## 3. Functionality Specification

### Core Features
- Responsive navigation with mobile hamburger menu
- Smooth scroll to sections on nav click
- Product category filtering (visual only)
- Form validation (required fields, email format)
- Scroll-triggered fade-in animations
- Sticky navigation on scroll

### User Interactions
- Click nav links → smooth scroll to section
- Hover product cards → lift + glow effect
- Click hamburger → toggle mobile menu
- Submit form → validation → success message
- Scroll → elements fade in

### Products to Display (6 total)
1. **Carbon Fiber Wing** - Wings category
2. **GT Wing Pro** - Wings category
3. **Front Splitter Elite** - Splitters category
4. **Race Splitter System** - Splitters category
5. **Rear Diffuser Carbon** - Diffusers category
6. **Venturi Diffuser Pro** - Diffusers category

---

## 4. Acceptance Criteria

- [ ] Page loads without errors
- [ ] Dark theme applied consistently
- [ ] Navigation is fixed and functional
- [ ] Mobile menu works on small screens
- [ ] Hero section displays properly on all devices
- [ ] Product grid is responsive (1/2/3 columns)
- [ ] Contact form validates inputs
- [ ] All hover effects work smoothly
- [ ] Scroll animations trigger correctly
- [ ] Typography is readable on all devices
- [ ] Orange accent color is used consistently
