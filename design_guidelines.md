# Fallimo.com Modern Clone - Design Guidelines

## Design Approach
**Reference-Based Approach** - Drawing inspiration from modern SaaS platforms like Stripe and Linear for clean layouts, subtle animations, and contemporary design systems while maintaining Fallimo's luxury transportation brand identity.

## Core Design Elements

### A. Color Palette
**Primary Brand Colors** (preserve existing Fallimo palette):
- Deep navy/black for headers and primary text
- Luxury gold accents for CTAs and highlights
- Clean whites and light grays for backgrounds

**Modern Enhancements**:
- Background: 248 100% 98% (soft white)
- Secondary text: 215 25% 27% (slate gray)
- Primary text: 222 84% 5% (near black)
- Card backgrounds: Pure white with subtle shadows

### B. Typography
- **Primary**: Inter font family via Google Fonts
- **Hierarchy**: Bold headlines (32-48px), medium subheadings (20-24px), regular body text (16px)
- **Weight variations**: 400 (regular), 500 (medium), 600 (semibold), 700 (bold)

### C. Layout System
**Tailwind spacing primitives**: Focus on units 4, 6, 8, 12, 16 for consistent spacing
- Padding: p-4, p-6, p-8 for cards and sections
- Margins: m-4, m-8, m-12 for element separation
- Gaps: gap-6, gap-8 for grid layouts

### D. Component Library

**Navigation**:
- Fixed header with Fallimo logo (left) and phone number (right)
- Hamburger menu for mobile with slide-out drawer
- Clean horizontal navigation for desktop

**Cards**:
- Vehicle showcase cards with rounded corners, subtle shadows
- Hover effects with gentle elevation increase
- Review cards with customer photos and star ratings

**Buttons**:
- Primary: Solid gold/brand color with white text
- Secondary: Outline style with brand color border
- For buttons over images: blurred background with outline variant

**Forms**:
- Clean input fields with subtle borders
- Date pickers for booking requests
- Dropdown selectors for vehicle types

**Image Galleries**:
- Grid layouts with 3-4 columns on desktop
- Lightbox overlay for full-size viewing
- Thumbnail navigation for vehicle interiors

### E. Page Structure

**Homepage**:
- Hero section with luxury vehicle imagery and prominent "Get Quote" CTA
- Service overview cards (Party Bus, Limousine, Exotic, Shuttle)
- Featured customer testimonials
- Contact section with service areas

**Fleet Pages**:
- Vehicle category headers with image galleries
- Specification lists and amenity highlights
- Embedded YouTube videos for vehicle tours
- Clear booking CTAs

**Services Pages**:
- Event-focused layouts (Corporate, Private, Shuttle)
- Use case scenarios with supporting imagery
- Pricing information and booking forms

**Reviews Page**:
- Google and Facebook review integration styling
- Customer photo testimonials in card format
- Star ratings and review excerpts
- Cashback offer highlights

## Images
- **Hero Image**: Large luxury party bus or limousine exterior shot with city/event backdrop
- **Vehicle Galleries**: High-quality interior and exterior photos for each vehicle type
- **Customer Photos**: Testimonial images from Google/Facebook reviews
- **Event Imagery**: Corporate and private event scenarios showing vehicles in use
- **Background Elements**: Subtle texture overlays for section breaks

## Visual Treatment
- **Shadows**: Subtle drop shadows on cards (shadow-sm, shadow-md)
- **Rounded Corners**: Consistent border radius (rounded-lg, rounded-xl)
- **Gradients**: Minimal use, primarily for hero overlays
- **Spacing**: Generous whitespace between sections
- **Animations**: Smooth transitions on hover states, fade-in effects on scroll