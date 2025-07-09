# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static landing page for Emryk™, a company focused on creating custom reasoning engines (RE) for high-functioning TBI patients. The site introduces their flagship product Tzu™, which is designed to be a private AI system that works with peer support specialists.

## Architecture

This is a simple static HTML website with the following structure:

- **index.html** - Main landing page with embedded CSS and complete styling
- **favicon.ico** - Site favicon
- **CNAME** - Domain configuration for GitHub Pages

The site is a single-page application using vanilla HTML, CSS, and minimal JavaScript. All styling is embedded in the HTML file using CSS custom properties (CSS variables) for theming.

## Key Features

- **Static Site**: No build process required - pure HTML/CSS
- **Responsive Design**: Mobile-first approach with CSS media queries
- **Form Integration**: Netlify form handling for beta signups
- **CSS Custom Properties**: Theme system using CSS variables for colors and styling
- **Animations**: CSS keyframe animations for fade-in effects

## Development Commands

Since this is a static site, no build commands are needed. Simply:

- Open `index.html` in a browser for local development
- Use a simple HTTP server if needed: `python -m http.server 8000`

## Deployment

The site is configured for GitHub Pages deployment:
- Domain configured via CNAME file
- Static files served directly from the repository
- Form submissions handled by Netlify

## Content Structure

The landing page includes:
- Hero section with company branding
- Product features highlighting privacy, open-source foundation, and human-in-the-loop approach
- Founder story section explaining the mission and personal motivation
- Beta signup form integrated with Netlify Forms
- Footer with copyright information

## Styling Notes

- Dark theme using CSS custom properties
- Color palette: dark backgrounds (#0A0E1A), light text (#E2E8F0), orange accents (#f78c2a)
- System font stack for cross-platform compatibility
- Grid background pattern using CSS gradients
- Responsive breakpoints at 640px for mobile optimization