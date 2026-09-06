# JavaScript Forms

Use JavaScript form handling only when browser HTML validation is not enough for the assignment. Start by listening for `submit`, inspect the form values, and prevent submission only when you have a clear reason.

```js
const form = document.querySelector("form");

form.addEventListener("submit", (event) => {
  // Check the values before deciding whether to continue.
});
```

Read [MDN form validation](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Forms/Form_validation) and [MDN `submit` event](https://developer.mozilla.org/en-US/docs/Web/API/HTMLFormElement/submit_event).
