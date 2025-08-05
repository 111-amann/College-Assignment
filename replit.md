# Overview

This is a static website for a Computer Science Department at Sanjivani University, located in Kopergaon, Maharashtra. The site provides information about the department's academic programs, faculty, courses, and contact details. It's built as a traditional multi-page HTML website with a shared CSS stylesheet and uses Font Awesome icons for visual enhancement. The site features a clean, professional design with a blue gradient color scheme and responsive layout principles.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Static HTML Multi-Page Structure**: Five main pages (index, about, courses, faculty, contact) with consistent navigation and layout
- **Shared Stylesheet Design**: Single `style.css` file provides consistent styling across all pages, with some pages having inline styles for specific content
- **Responsive Layout**: CSS Grid and Flexbox-based layouts designed for multiple screen sizes
- **Icon Integration**: Font Awesome CDN integration for consistent iconography throughout the interface

## Design System
- **Color Scheme**: Professional blue gradient theme using CSS custom properties for consistency
- **Typography**: Segoe UI font stack for cross-platform compatibility
- **Component Structure**: Reusable CSS classes for cards, buttons, navigation, and content sections
- **Visual Hierarchy**: Clear heading structure and consistent spacing using CSS reset and base styles

## Content Management
- **Static Content Delivery**: All content is hardcoded in HTML files, making it suitable for simple hosting solutions
- **Image Handling**: External image sources via Pixabay CDN for faculty photos and hero images
- **Navigation System**: Consistent multi-page navigation with active state indicators

# External Dependencies

## CDN Services
- **Font Awesome 6.0.0**: Icon library loaded from cdnjs.cloudflare.com for consistent iconography
- **Pixabay**: External image hosting service for faculty portraits and hero section imagery

## Browser Dependencies
- **Modern CSS Features**: Relies on CSS Grid, Flexbox, and CSS3 features supported in modern browsers
- **Web Fonts**: System font stack fallback ensures compatibility across different operating systems

Note: This is a purely frontend static website with no backend services, databases, or server-side processing required.