# DOM

The Document Object Model (DOM) represents an HTML document as objects JavaScript can inspect and change.

A simple learning sequence is:

1. Select an element with `querySelector`.
2. Read or change a property.
3. Confirm the change in the browser.

```js
const heading = document.querySelector("h1");
heading.textContent = "Updated heading";
```

Read [MDN Document Object Model](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model) and [MDN `querySelector`](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector).
