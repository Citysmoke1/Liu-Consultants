# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for Liu Consultancy - a professional consultancy firm offering web development, data analysis, mathematical consultancy, app development, environmental & civil engineering, and geospatial analysis services. The site is designed as a professional business website with Australian contact information and comprehensive service offerings.

## Architecture

**Multi-Page Static Website**
- `index.html` - Main landing page with embedded CSS/JS containing hero, services, pricing, and contact sections
- `contact.html` - Dedicated contact page with comprehensive contact form and business information
- `Footer/` - Directory containing footer page content (about-us.html, professional-qualifications.html, service pages, etc.)
- `Header/` - Directory containing header page content (documents.html)
- `Assets/` - Directory containing images, icons, and visual assets organized by purpose
- All styling is embedded within each HTML file using `<style>` tags
- JavaScript functionality is embedded at the bottom of each HTML file

**Key Features:**
- Fixed navigation header with logo and documents link
- Hero section with background image and call-to-action buttons
- Services grid showcasing 6 service categories with detailed feature lists
- Comprehensive pricing section with detailed service tiers
- Professional contact information and business hours
- Footer with professional qualifications and company credentials

## Development Commands

Since this is a static HTML website, there are no build processes or package managers:

**Local Development:**
- Open `index.html` directly in a web browser
- Use a local web server for development: `python -m http.server 8000` or `npx serve .`

**No Build/Test Commands:**
- No package.json, build tools, or testing frameworks
- Changes are immediately visible by refreshing the browser

## Code Structure

**Color Scheme:**
- Primary gradient: rgb(25, 55, 130) to rgb(65, 105, 180) (blue theme)
- Accent color: #ff6b6b (red for highlights)
- Background gradients for sections using complementary grays (#e9ecef to #ced4da)

**Styling Approach:**
- All CSS is embedded in the `<head>` section of each HTML file
- Uses CSS Grid and Flexbox for responsive layouts
- Mobile-first responsive design with breakpoint at 768px
- Consistent styling patterns across all pages

**JavaScript Features:**
- Intersection Observer API for scroll animations
- Smooth scrolling navigation
- Fade-in animations for service cards and contact items
- Form validation and submission handling on contact page

**Asset Organization:**
- Service icons in `Assets/` directory with descriptive naming
- Contact icons in `Assets/Get_In_Touch/` subdirectory
- Hero background image and company logo in main Assets directory

**Content Organization:**
- Services organized in a 6-card grid layout (Web Dev, Data Analysis, Mathematical Consultancy, App Development, Environmental Engineering, Geospatial Analysis)
- Professional credentials and qualifications prominently displayed
- Australian business information: Brisbane location, AUD pricing, AEST business hours
- Comprehensive pricing structure with detailed service tiers
- Financial engineering expertise maintained through data analysis offerings