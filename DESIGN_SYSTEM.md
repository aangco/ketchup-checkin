# KetchUp Design System

## Overview
The KetchUp Design System provides a comprehensive set of design tokens, components, and guidelines to ensure consistency, accessibility, and a delightful user experience across the doctor's office check-in application.

## 🎨 Color Palette

### Primary Colors
- **Primary Base**: `#DECEB7` - Warm beige, main brand color
- **Primary Light**: `#F0E8D8` - Lighter variant for backgrounds
- **Primary Dark**: `#C4B89A` - Darker variant for hover states

### Secondary Colors
- **Blue**: `#4A90E2` - Primary actions, links, focus states
- **Green**: `#7ED321` - Success states, confirmations
- **Orange**: `#F5A623` - Warnings, attention
- **Red**: `#D0021B` - Errors, destructive actions

### Neutral Colors
- **White**: `#FFFFFF` - Primary backgrounds
- **Light Gray**: `#F8F9FA` - Secondary backgrounds
- **Medium Gray**: `#E9ECEF` - Borders, dividers
- **Dark Gray**: `#6C757D` - Secondary text
- **Darker Gray**: `#495057` - Primary text
- **Black**: `#212529` - Headings, emphasis

### Semantic Colors
- **Success**: `#28A745` - Positive feedback
- **Warning**: `#FFC107` - Caution states
- **Error**: `#DC3545` - Error messages
- **Info**: `#17A2B8` - Informational content

## 📝 Typography

### Font Family
- **Primary**: Inter (Google Fonts)
- **Fallback**: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif

### Font Sizes
- **XS**: `0.75rem` (12px) - Captions, labels
- **SM**: `0.875rem` (14px) - Small text, secondary content
- **Base**: `1rem` (16px) - Body text, default
- **LG**: `1.125rem` (18px) - Large body text
- **XL**: `1.25rem` (20px) - Subheadings
- **XXL**: `1.5rem` (24px) - Section headings
- **XXXL**: `2rem` (32px) - Page titles

### Font Weights
- **Light**: 300 - Subtle emphasis
- **Regular**: 400 - Body text
- **Medium**: 500 - Labels, buttons
- **Semi-bold**: 600 - Subheadings
- **Bold**: 700 - Main headings

### Line Heights
- **Tight**: 1.2 - Headings
- **Normal**: 1.6 - Body text
- **Relaxed**: 1.8 - Large text blocks

## 📏 Spacing System

### 8px Grid System
- **XS**: `0.25rem` (4px) - Minimal spacing
- **SM**: `0.5rem` (8px) - Small spacing
- **MD**: `1rem` (16px) - Standard spacing
- **LG**: `1.5rem` (24px) - Large spacing
- **XL**: `2rem` (32px) - Extra large spacing
- **XXL**: `3rem` (48px) - Section spacing

### Component Spacing
- **Form Groups**: `var(--spacing-md)` (16px)
- **Sections**: `var(--spacing-xl)` (32px)
- **Page Margins**: `var(--spacing-lg)` (24px)
- **Button Padding**: `var(--spacing-sm) var(--spacing-md)` (8px 16px)

## 🔲 Border Radius

- **Small**: `0.25rem` (4px) - Buttons, small elements
- **Medium**: `0.5rem` (8px) - Cards, form inputs
- **Large**: `1rem` (16px) - Large cards, containers
- **Extra Large**: `1.5rem` (24px) - Hero sections

## 🌟 Shadows

- **Small**: `0 1px 3px rgba(0, 0, 0, 0.12), 0 1px 2px rgba(0, 0, 0, 0.24)`
- **Medium**: `0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23)`
- **Large**: `0 10px 20px rgba(0, 0, 0, 0.19), 0 6px 6px rgba(0, 0, 0, 0.23)`

## ⚡ Transitions

- **Fast**: `0.15s ease-in-out` - Hover effects, focus states
- **Normal**: `0.3s ease-in-out` - Page transitions, animations
- **Slow**: `0.5s ease-in-out` - Complex animations

## 📱 Responsive Breakpoints

### Mobile-First Approach
- **Mobile**: `320px` - Base styles
- **Tablet**: `768px` - Medium screens
- **Desktop**: `1024px` - Large screens
- **Wide**: `1200px` - Extra large screens

### Container Max-Widths
- **Mobile**: 100% - Full width
- **Tablet**: `720px` - Centered with margins
- **Desktop**: `960px` - Centered with margins
- **Wide**: `1200px` - Centered with margins

## ♿ Accessibility Standards

### WCAG 2.1 AA Compliance
- **Color Contrast**: Minimum 4.5:1 for normal text, 3:1 for large text
- **Focus Indicators**: Clear, visible focus states
- **Touch Targets**: Minimum 44px × 44px for interactive elements
- **Screen Reader**: Proper ARIA labels and semantic HTML

### Focus Management
- **Focus Outline**: 2px solid `var(--secondary-blue)` with 2px offset
- **Skip Links**: Hidden by default, visible on focus
- **Tab Order**: Logical, intuitive navigation flow

### Motion & Animation
- **Reduced Motion**: Respects `prefers-reduced-motion` preference
- **Animation Duration**: Maximum 500ms for complex animations
- **Hover States**: Provide alternative focus states

## 🧩 Component Guidelines

### Button Components
- **Primary**: Primary actions, main CTAs
- **Secondary**: Secondary actions, alternative options
- **Tertiary**: Text links, subtle actions
- **Size Variants**: Small, medium, large
- **States**: Default, hover, focus, active, disabled

### Form Components
- **Input Fields**: Consistent styling, clear labels
- **Validation States**: Success, error, warning indicators
- **Required Fields**: Clear indication of mandatory fields
- **Error Messages**: Helpful, actionable feedback

### Card Components
- **Elevation**: Subtle shadows for depth
- **Padding**: Consistent internal spacing
- **Borders**: Optional borders for definition
- **Hover States**: Subtle interactions

## 🎭 Mascot Design Guidelines

### Character Design
- **Style**: Abstract, friendly, gender-neutral
- **Colors**: Consistent with primary color palette
- **Expressions**: Welcoming, encouraging, helpful
- **Animations**: Smooth, purposeful movements

### Interaction States
- **Idle**: Subtle breathing animation
- **Speaking**: Lip sync or expression changes
- **Guiding**: Pointing, gesturing animations
- **Celebrating**: Success animations, confetti

### Accessibility
- **Alt Text**: Descriptive text for screen readers
- **Animation Control**: Respects motion preferences
- **Focus States**: Keyboard navigation support

## 📋 Implementation Notes

### CSS Custom Properties
All design tokens are implemented as CSS custom properties for easy theming and maintenance.

### Component Library
Components are built with accessibility and reusability in mind, following React best practices.

### Testing
All components include accessibility testing and cross-browser compatibility verification.

---

**Version**: 1.0  
**Last Updated**: December 2024  
**Next Review**: January 2025
