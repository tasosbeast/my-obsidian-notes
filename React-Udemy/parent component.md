
A **parent component** in [[React]] is a component that **renders and manages one or more child [[components]]**. It is responsible for **passing down [[props]]**, managing [[state]] (if lifted), and sometimes controlling the layout or [[structure]] of its children.

Parent-child relationships form the core of [[React]]’s **[[components|component-based]] architecture**, enabling **[[component composition|composition]]** and **[[reusability]]**. The parent component can:

- Provide [[data]] via [[props]]
    
- Handle events triggered by children
    
- Control what is rendered conditionally
    

Example:

```js
function Parent() {
  const name = "Tasos";
  return <ChildComponent name={name} />;
}
```

Understanding parent-child relationships is key to managing [[data flow]], especially in apps with deep or nested component trees.
