# Form Validation

## Problem

Users need clear feedback when submitted values are missing or invalid.

## Approach

1. Choose the correct HTML input type.
2. Add built-in constraints such as `required`, `minlength`, or `pattern` when appropriate.
3. Add visible instructions before adding custom JavaScript.
4. If custom feedback is needed, connect it to the control with an accessible relationship.

Read [MDN client-side form validation](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms/Form_validation).

## Common mistakes

- Relying only on color to show an error.
- Removing the browser's useful validation without replacing it.
- Giving feedback that is not associated with the invalid control.
