# JavaScript Modules

Modules divide JavaScript into focused files. Export only what another file needs and import it with a clear path.

```js
// helper.js
export function formatValue(value) {
  return value.trim();
}

// main.js
import { formatValue } from "./helper.js";
```

Read [MDN JavaScript modules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules).
