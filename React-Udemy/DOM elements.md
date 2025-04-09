**[[DOM]] elements** are the building blocks of the [[DOM]] (Document Object Model). Each element in an [[HTML]] document — such as `<div>`, `<p>`, or `<button>` — becomes a node in the [[DOM]] tree that can be accessed and modified through [[JavaScript]].

In **Vanilla [[JavaScript]]**, developers interact with [[DOM]] elements using [[methods]] like `getElementById`, `querySelector`, or by dynamically creating elements with `document.createElement`. These elements can be modified directly via properties like `innerText`, `classList`, or `style`.

In [[React]], developers rarely interact with [[DOM]] elements directly. Instead, the UI is described using [[JSX]], and [[React]] manages [[DOM]] elements internally via the [[Virtual DOM]], enabling more efficient and [[declarative]] updates.