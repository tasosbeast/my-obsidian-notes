
A **child component** in [[React]] is a component that is **rendered inside a [[parent component]]**. It receives [[data]] and behavior via [[props]] and is responsible for rendering part of the [[User Interface (UI)]].

Child [[components]] promote **[[modularity]]** and [[reusability]] by isolating functionality into smaller, focused units. While a child component can render independently, it often relies on its [[parent component]] to provide dynamic [[data]] or handle events.

Example:

```js
function Child({ name }) {
  return <p>Hello, {name}!</p>;
}
```

Child [[components]] can also communicate **upward** to their parent using **callback [[props]]**, enabling interactivity and controlled [[data flow]] in a [[components|component]]-based architecture.
