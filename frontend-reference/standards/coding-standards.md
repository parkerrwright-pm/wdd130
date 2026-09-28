# Coding Standards

- Use semantic HTML5 and meaningful names.
- Choose a tag for its content meaning; do not wrap every item in a `div`.
- Keep text in a paragraph, heading, link, or list item instead of leaving it
	directly in structural elements.
- Use CSS for text appearance. Do not use heading or HTML formatting elements
	merely to change appearance in WDD 130.
- Use Grid for major layouts and Flexbox for related items inside those areas
	when the lesson requires layout.
- Treat the footer as the visual end of the page. Give it a distinct muted
	background color and enough padding to separate it from the main content.
- Avoid pure black and white for page or footer backgrounds; use nearby shades
	such as `#242321`, `#414141`, `#cdcdcd`, or `#eff1f0` when appropriate.
- Use kebab-case for file and class names in this repository.
- Keep HTML, CSS, and JavaScript in separate files.
- Indent consistently and keep examples easy to scan.
- Prefer the simplest rule that demonstrates the lesson.
- Remove unused markup and styles.
- Test one change at a time so errors are easier to locate.

## CSS Organization and Color Consistency

- Put `:root` custom properties at the top of the stylesheet.
- Follow variables with the universal reset and default HTML element rules.
- Place shared content defaults after the defaults, followed by shared header and footer styling.
- Group reusable classes next, then place rules used by individual pages in page-specific sections.
- Keep related selectors together and avoid duplicate rules. When selectors overlap, later declarations can override earlier declarations, so order should be intentional.
- Prefer a consistent color notation within a stylesheet (for example, hex values). Mixed notations such as named colors, hex, and `rgb()` can suggest inconsistent styling, but are not inherently invalid. Use alpha/transparency where needed and choose a notation that clearly expresses it.

Use [HTML tag selection](../html/tag-selection.html), [MDN HTML elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element), and [MDN CSS reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference) to verify platform details.
