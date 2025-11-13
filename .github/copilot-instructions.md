# Copilot Instructions - Psicologia Social

## Project Overview
This is a static website for "Taller Sin Límites" (Workshop Without Limits), an inclusive creative workshop for adults with Down syndrome. The project focuses on accessibility, inclusivity, and creativity.

**Project Language:** Spanish (es)
**Tech Stack:** HTML5, CSS3, Vanilla JavaScript
**Purpose:** Informational website showcasing inclusive workshop services

## Project Structure
```
.
├── index.html          # Main HTML file with embedded styles and scripts
├── style.css           # External CSS styles (currently in use)
├── .vscode/            # VS Code configuration
│   └── settings.json   # Live Server configuration (port 5501)
└── .github/            # GitHub configuration and instructions
```

## Coding Conventions

### HTML
- Use semantic HTML5 elements
- Maintain proper accessibility attributes (ARIA labels, alt text, etc.)
- Keep language attribute as `lang="es"` for Spanish content
- Ensure all interactive elements are keyboard accessible
- Maintain consistent indentation (4 spaces)

### CSS
- Use descriptive class names in Spanish when appropriate
- Follow the existing pastel color palette:
  - Primary blue: `#a8dadc`
  - Cream: `#ffe8d6`
  - Lilac: `#cdb4db`
  - Pink: `#ffcad4`
  - Light blue: `#bde0fe`
  - Accent red: `#e63946`
- Keep the Lexend font family for consistency
- Maintain responsive design principles
- Use flexbox for layouts as currently implemented

### JavaScript
- Use vanilla JavaScript (no frameworks)
- Write clean, readable functions
- Use modern ES6+ syntax
- Add comments in Spanish for complex logic
- Ensure all scripts are accessible and keyboard-friendly

## Accessibility Guidelines
**CRITICAL:** This website serves people with diverse abilities. Always prioritize accessibility:

- Maintain high contrast ratios for text
- Ensure all interactive elements are keyboard navigable
- Use clear, simple language (Plain Spanish)
- Keep font sizes readable (minimum 16px for body text)
- Test with screen readers when possible
- Avoid complex animations that could be disorienting
- Ensure forms and buttons have clear labels

## Development Workflow

### Testing
- Open `index.html` in a browser to test changes
- Test in multiple browsers (Chrome, Firefox, Safari, Edge)
- Verify mobile responsiveness
- Check keyboard navigation works correctly
- Validate HTML at https://validator.w3.org/
- Test color contrast for accessibility

### Local Development
- Use Live Server (configured on port 5501) for development
- No build process required - this is a static site
- All changes are immediately viewable in browser

## What to Modify
✅ **You CAN modify:**
- HTML content and structure in `index.html`
- CSS styles in `style.css` or embedded styles
- JavaScript functionality for tabs and interactions
- Add new sections or features
- Improve accessibility
- Fix bugs or broken links
- Update content while maintaining the inclusive message

❌ **You SHOULD NOT modify:**
- The core mission and inclusive message of the site
- Language from Spanish to another language (unless specifically requested)
- `.vscode/settings.json` (unless fixing configuration issues)
- Remove accessibility features

## Special Considerations

### Inclusive Language
- Use gender-neutral and inclusive Spanish language
- Maintain the welcoming and positive tone
- Respect the focus on adults with Down syndrome
- Keep content clear and easy to understand

### Content Guidelines
- All content should be welcoming and inclusive
- Avoid jargon or complex terminology
- Keep navigation simple and intuitive
- Maintain the creative and artistic theme

### Color and Design
- Stick to the soft, pastel color palette
- Avoid harsh or high-contrast color combinations
- Keep the design clean and uncluttered
- Maintain good spacing for readability

## Common Tasks

### Adding a New Section
1. Add HTML structure in `index.html`
2. Style with existing CSS classes or add new ones
3. Ensure responsive behavior
4. Test keyboard navigation
5. Verify accessibility

### Updating Content
1. Locate the section in `index.html`
2. Update text while maintaining HTML structure
3. Keep language simple and inclusive
4. Test visual appearance in browser

### Fixing Bugs
1. Identify the issue location (HTML, CSS, or JS)
2. Make minimal changes to fix the problem
3. Test thoroughly in multiple browsers
4. Ensure no accessibility regressions

## Resources
- MDN Web Docs: https://developer.mozilla.org/es/
- WCAG Accessibility Guidelines: https://www.w3.org/WAI/WCAG21/quickref/
- HTML Validator: https://validator.w3.org/

## Notes
- The site currently has some minor issues (incomplete Google Fonts link on line 17, truncated navigation on lines 162-163) that could be fixed
- No external dependencies or package manager needed
- All code should be readable and maintainable
- Prioritize user experience and accessibility over complex features
