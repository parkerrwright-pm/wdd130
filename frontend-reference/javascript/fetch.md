# Fetch

The Fetch API requests a resource and returns a Promise. Handle the response status before using its data.

```js
fetch("/data/example.json")
  .then((response) => {
    if (!response.ok) {
      throw new Error("Request failed");
    }
    return response.json();
  })
  .then((data) => {
    // Decide how the returned data should be displayed.
  });
```

Read [MDN Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API) and [MDN `Response.ok`](https://developer.mozilla.org/en-US/docs/Web/API/Response/ok).
