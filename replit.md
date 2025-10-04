# Fallimo Luxury Transportation

## Overview

Fallimo is a modern luxury transportation service website offering party bus and limousine rentals across NY, NJ, CT, and PA. The application is built as a full-stack web solution with a React frontend showcasing the company's fleet, services, testimonials, and an integrated quote request system. The platform emphasizes premium user experience with modern design patterns inspired by SaaS platforms like Stripe and Linear.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Framework**: React with TypeScript using Vite as the build tool
- **Routing**: Wouter for lightweight client-side routing
- **UI Library**: Shadcn/ui components built on Radix UI primitives
- **Styling**: Tailwind CSS with custom design system following modern SaaS aesthetics
- **State Management**: TanStack Query (React Query) for server state management
- **Forms**: React Hook Form with Zod validation for type-safe form handling

### Backend Architecture
- **Runtime**: Node.js with Express.js server
- **Language**: TypeScript throughout the stack
- **API Design**: RESTful endpoints with structured error handling
- **Validation**: Zod schemas for runtime type validation
- **Database ORM**: Drizzle ORM for type-safe database operations

### Data Storage
- **Database**: PostgreSQL as the primary database
- **Connection**: Neon serverless PostgreSQL driver (@neondatabase/serverless)
- **Schema Management**: Drizzle Kit for migrations and schema management
- **Models**: Users table for authentication and quote_requests table for customer inquiries

### Design System
- **Typography**: Inter font family for modern, clean readability
- **Color Palette**: Navy/black primary colors with luxury gold accents, maintaining Fallimo's brand identity
- **Component Library**: Comprehensive UI components including cards, forms, navigation, and testimonials
- **Responsive Design**: Mobile-first approach with breakpoint-based layouts
- **Visual Effects**: Subtle hover effects, elevation changes, and smooth transitions

### Email Integration
- **Service**: SendGrid for transactional email delivery
- **Functionality**: Automated quote request notifications sent to business owners
- **Error Handling**: Non-blocking email delivery with graceful fallback

## External Dependencies

### Core Infrastructure
- **Database**: Neon PostgreSQL serverless database
- **Email Service**: SendGrid API for transactional emails
- **Build & Development**: Vite development server with hot module replacement

### UI and Component Libraries
- **Radix UI**: Comprehensive set of accessible, unstyled UI primitives
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development
- **Lucide React**: Icon library for consistent iconography
- **Class Variance Authority**: Utility for managing component variants

### Development Tools
- **TypeScript**: Static type checking across the entire stack
- **ESBuild**: Fast JavaScript bundler for production builds
- **Drizzle Kit**: Database migration and introspection tools
- **Replit Integration**: Development environment optimizations and error handling

### Fonts and Assets
- **Google Fonts**: Inter, DM Sans, Fira Code, Geist Mono, and Architects Daughter
- **Static Assets**: Generated images for fleet vehicles and branding materials stored in attached_assets directory

## WordPress Conversion (October 2025)

### Elementor-Based WordPress Solution
A complete WordPress conversion with 100% feature parity, rebuilt specifically for **visual editing with Elementor**. User can edit all content visually without any coding.

### Package Contents
- **fallimo-elementor-theme.tar.gz** (4.8KB): Minimal theme with header/footer only
- **fallimo-elementor-toolkit.tar.gz** (15KB): Comprehensive plugin with 6 custom Elementor widgets

### Custom Elementor Widgets Created
1. **Quote Form Widget** - Full SendGrid integration, professional email templates
2. **Fleet Grid Widget** - Dynamic vehicle display with category filters, video links
3. **Services Grid Widget** - All 6 services with icons and features
4. **Testimonials Widget** - Customer reviews with star ratings
5. **Video Gallery Widget** - 5 YouTube party bus tour videos embedded
6. **FAQ Widget** - Accordion-style Q&A with 8 questions

### Key Features
- **100% Elementor Editable**: All pages built with drag-and-drop widgets
- **Auto-Import System**: 15 vehicles, 6 services, 6+ testimonials import on activation
- **4 Pages Auto-Created**: Home, Fleet, Services, Reviews (all editable in Elementor)
- **SendGrid Integration**: Professional HTML email notifications for quotes
- **Complete Header**: Logo, navigation, phone, mobile menu
- **Complete Footer**: All 6 social links (Facebook, Instagram, Pinterest, TikTok, Yelp, YouTube), contact info, services list
- **Video Gallery**: 5 YouTube embeds (12-pass, 15-pass, 24-pass, 28-pass, 30-pass party buses)
- **Dynamic Content**: Widgets pull data from custom post types automatically
- **Responsive Design**: Mobile-first, works on all devices

### Color Scheme Maintained
- Black background (#000000)
- Purple primary (#4f3c9a)
- Pink secondary (#D14C79)
- Yellow accent (#fcfa7e)

### Technical Architecture
- **Minimal Theme**: Only handles header/footer navigation
- **Plugin-Based Functionality**: All features in Elementor Toolkit plugin
- **Custom Post Types**: Fleet, Services, Testimonials
- **Elementor Integration**: Custom widget category with 6 widgets
- **SendGrid API**: Professional quote notification system
- **Auto-Activation**: Data import and page creation on plugin activation

### Documentation
- **ELEMENTOR-INSTALLATION-GUIDE.md**: Complete installation and usage guide with Elementor editing instructions