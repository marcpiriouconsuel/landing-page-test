# Accessibility Features - Consuel Landing Page

This landing page has been built with WCAG 2.1 AA compliance in mind. Below are the accessibility features implemented:

## Semantic HTML Structure

- **Proper HTML5 landmarks**: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- **Heading hierarchy**: Logical H1-H3 structure for screen readers
- **Language declaration**: `lang="fr"` for French content

## ARIA Support

- **Navigation landmark**: `role="navigation"` with `aria-label="Navigation principale"`
- **Region landmarks**: All major sections have `role="region"` with descriptive labels
- **Banner and contentinfo**: Proper header and footer roles
- **Labelledby references**: Sections linked to their headings via `aria-labelledby`
- **Hidden decorative elements**: SVG icons marked with `aria-hidden="true"`

## Keyboard Navigation

- **Focus indicators**: Clear visual focus with outline styling
- **Tab order**: Logical keyboard navigation flow
- **Focus management**: Smooth scroll with focus shift on anchor clicks
- **Skip links**: CSS structure ready for skip-to-content links

## Visual Accessibility

- **Color contrast**: All text meets WCAG AA contrast ratios
  - Primary text: #2C3E50 on white background
  - Secondary text: #5A6C7D on white background
  - Buttons: White text on #00A2DE background
- **Focus visible**: 3px outline with offset for all interactive elements
- **Hover states**: Clear visual feedback on interactive elements

## Responsive Design

- **Viewport meta tag**: Proper mobile scaling
- **Flexible layouts**: Grid and flexbox for responsive content
- **Touch targets**: Adequate size for buttons and links (minimum 44x44px)
- **Text scaling**: Responsive font sizes using rem/em units

## Reduced Motion Support

```css
@media (prefers-reduced-motion: reduce) {
    /* Disables animations for users with motion sensitivity */
}
```

## High Contrast Mode

```css
@media (prefers-contrast: high) {
    /* Enhanced borders for better visibility */
}
```

## Screen Reader Friendly

- **Descriptive link text**: No "click here" links
- **Alt text**: Decorative images properly hidden
- **Form labels**: (N/A - no forms in this landing page)
- **Skip navigation**: Structure supports skip links

## Print Accessibility

- **Print styles**: Optimized for printing
- **URL display**: External links show URLs when printed
- **Clean layout**: Unnecessary elements hidden in print view

## Testing Recommendations

To verify accessibility:

1. **Keyboard navigation**: Tab through all interactive elements
2. **Screen reader**: Test with NVDA (Windows) or VoiceOver (Mac)
3. **Color contrast**: Use tools like WebAIM Contrast Checker
4. **Browser zoom**: Test at 200% zoom level
5. **Mobile devices**: Test on actual mobile devices
6. **Automated tools**: Run Lighthouse, axe DevTools, or WAVE

## Browser Compatibility

Tested and compatible with:
- Chrome/Edge (Chromium)
- Firefox
- Safari
- Mobile browsers (iOS Safari, Chrome Mobile)

## Further Improvements

Potential enhancements for even better accessibility:
- Add skip-to-content link at the top
- Implement live region announcements for dynamic content
- Add language switches if multiple languages are needed
- Include a sitemap for complex navigation

---

For questions or suggestions about accessibility, please open an issue in the repository.
