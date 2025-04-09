
In a typical [[React]] [[application]], the [[HTML]] file includes a `<div>` element with `id="root"`. This element serves as the **mount point** for the entire [[React]] component tree.

[[React]] uses the `ReactDOM.createRoot()` or `ReactDOM.render()` method to attach the top-level [[component]] (usually `<App />`) to this div.

Example in `index.html`:

```html
<body>
  <div id="root"></div>
</body>
```

And in `main.js` or `index.js`:

```js
import React from 'react';
import ReactDOM from 'react-dom/client';
import App from './App';

ReactDOM.createRoot(document.getElementById('root')).render(<App />);
```

Using `id="root"` is a **convention**, not a requirement — but it's widely adopted across the [[React]] ecosystem and [[tooling]].

---

Would you like to follow up with notes like `[[ReactDOM]]`, `[[mounting]]`, or `[[App component]]`?