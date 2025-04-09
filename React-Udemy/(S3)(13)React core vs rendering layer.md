
When using [[React]] via `<script>` tags (without [[bundlers]]), two separate [[libraries]] are loaded:

1. **[[React]] core [[libraries|library]]**
    

```html
<script src="https://unpkg.com/react@18/umd/react.development.js"></script>
```

This contains the **core functionality** of [[React]]: component creation, [[hooks]] (`useState`, `useEffect`, etc.)[[useState]][[useEffect]], [[state]] management, and the [[reactive]] rendering logic. It defines how a [[React]] app works internally.

2. **React DOM (rendering layer)**
    

```html
<script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
```

This provides the **rendering engine** that connects React with the [[DOM]]. It enables React components to be rendered into the page — typically into an element like [[(S3)(13)Το id=root είναι το προεπιλεγμένο σημείο σύνδεσης (mount point) στη React|id="root"]].

React is designed to be platform-agnostic. `react-dom` is one rendering target, while others like `react-native` are used for mobile.
