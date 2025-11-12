# Copilot Instructions

## Project Overview

This is a personal portfolio website for Sanjay Kumar S, a MERN Full-Stack Developer. The project is a static website built with HTML, CSS, and JavaScript, showcasing skills, experience, education, and portfolio projects.

**Technology Stack:**
- HTML5
- CSS3
- JavaScript (vanilla)
- Font Awesome icons

## Project Structure

```
/
├── index.html          # Main HTML file with portfolio content
├── portfolio.css       # Stylesheet for the portfolio
└── images/            # Directory containing images used in the portfolio
```

## Coding Standards

### HTML
- Use semantic HTML5 elements where appropriate
- Maintain proper indentation (4 spaces)
- Use lowercase for element names and attributes
- Keep the structure clean and organized with comments for major sections
- Ensure accessibility with proper alt attributes for images

### CSS
- Use meaningful class names that describe purpose, not appearance
- Maintain consistent spacing and indentation (4 spaces)
- Group related styles together
- Add comments for major sections
- Follow mobile-first responsive design principles
- Use CSS custom properties (variables) for repeated values when possible

### JavaScript
- Use modern ES6+ syntax
- Keep functions small and focused on a single purpose
- Use meaningful variable and function names
- Add comments for complex logic
- Avoid inline event handlers when possible (prefer addEventListener)

## Development Workflow

### Making Changes
1. Test changes locally by opening `index.html` in a web browser
2. Verify responsive behavior by testing different screen sizes
3. Check that all interactive elements (menu, tabs, links) work correctly
4. Validate HTML and CSS syntax

### Testing
- **Manual Testing**: Open `index.html` in multiple browsers (Chrome, Firefox, Safari)
- **Responsive Testing**: Test on different viewport sizes (mobile, tablet, desktop)
- **Functionality Testing**: Verify all interactive elements work (navigation menu, tabs, form submissions)

### Validation
- Use W3C HTML Validator for HTML validation
- Use W3C CSS Validator for CSS validation
- Test all links to ensure they point to valid destinations

## Best Practices

### General
- Keep the codebase simple and maintainable
- Don't add unnecessary dependencies or frameworks
- Maintain the existing structure and style unless specifically requested
- Ensure all changes are backwards compatible

### Security
- Don't commit any sensitive information (API keys, personal data, credentials)
- Validate and sanitize any user inputs if forms are added
- Use HTTPS for external resources

### Performance
- Optimize images before adding them to the project
- Minimize inline styles
- Keep CSS and JavaScript files organized and efficient

## Common Tasks

### Adding a New Section
1. Add semantic HTML structure in `index.html`
2. Style the section in `portfolio.css` following existing patterns
3. Test responsive behavior
4. Update navigation if needed

### Modifying Styles
1. Locate the relevant CSS rules in `portfolio.css`
2. Make minimal changes to achieve the desired effect
3. Test across different screen sizes
4. Ensure changes don't break existing layouts

### Adding Interactive Features
1. Consider if vanilla JavaScript is sufficient before adding libraries
2. Add JavaScript at the end of the HTML body or in a separate file
3. Use event delegation for better performance
4. Test functionality across browsers

## Branch Management

- Only push changes to `copilot/*` branches
- Keep commits focused and atomic
- Write clear, descriptive commit messages

## Contact

For questions about the portfolio content or design decisions, refer to the existing structure and maintain consistency with the current design aesthetic.
