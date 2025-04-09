
Σε μια τυπική [[React]] [[εφαρμογή|εφαρμογή]], το αρχείο [[HTML]] περιλαμβάνει ένα στοιχείο `<div>` με `id="root"`. Αυτό το στοιχείο χρησιμεύει ως το **mount point** για  όλη η δομή των [[components]]

Η [[React]] χρησιμοποιεί τις μεθόδους `ReactDOM.createRoot()` ή `ReactDOM.render()`  για να **τοποθετήσει** το κορυφαίο [[component]] μέσα στο `div`

📄 Παράδειγμα στο `index.html`:

```html
<body>
  <div id="root"></div>
</body>
```

📁 Παράδειγμα στο `main.js` ή `index.js`:

```js
import React from 'react';
import ReactDOM from 'react-dom/client';
import App from './App';

ReactDOM.createRoot(document.getElementById('root')).render(<App />);
```

Η χρήση του `id="root"` είναι μια **σύμβαση** (convention) και όχι απαίτηση — όμως υιοθετείται ευρέως στο React οικοσύστημα και στα εργαλεία [[tooling]] που το υποστηρίζουν.
