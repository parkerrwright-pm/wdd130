# Events

An event is something that happens in the browser, such as a click or key press. An event listener connects that occurrence to a function.

```js
const button = document.querySelector("button");

button.addEventListener("click", () => {
  // Decide what this action should do.
});
```

Read [MDN Event reference](https://developer.mozilla.org/en-US/docs/Web/Events) and [MDN `addEventListener`](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener).
