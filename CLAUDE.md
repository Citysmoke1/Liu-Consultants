# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website for Liu Consultancy - a professional consultancy firm offering web development, data analysis, mathematical consultancy, app development, civil engineering, and financial planning services.

## Architecture

**Single-Page Static Website**
- `index.html` - Main HTML file containing all content, CSS, and JavaScript
- `Assets/` - Directory containing images and icons for the website
- All styling is embedded within the HTML file using `<style>` tags
- JavaScript functionality is embedded at the bottom of the HTML file

**Key Sections:**
- Header with navigation (fixed position)
- Hero section with company branding
- Services grid showcasing 6 service categories
- Contact information section
- Comprehensive footer with professional credentials

## Development Commands

Since this is a static HTML website, there are no build processes or package managers:

**Local Development:**
- Open `index.html` directly in a web browser
- Use a local web server for development: `python -m http.server 8000` or `npx serve .`

**No Build/Test Commands:**
- No package.json, build tools, or testing frameworks
- Changes are immediately visible by refreshing the browser

## Code Structure

**Styling Approach:**
- All CSS is embedded in the `<head>` section
- Uses CSS Grid and Flexbox for responsive layouts
- CSS custom properties for colors: primary gradient (#667eea to #764ba2), accent (#ff6b6b)
- Mobile-first responsive design with breakpoint at 768px

**JavaScript Features:**
- Intersection Observer API for scroll animations
- Smooth scrolling navigation
- Fade-in animations for service cards and contact items

**Content Organization:**
- Services are organized in a grid layout with consistent card structure
- Professional credentials prominently displayed in footer
- Contact information includes email, phone, and physical address