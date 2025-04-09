
**`useEffect`** is a built-in [[React]] **[[hooks|hook]]** used to handle **side effects** in functional [[components]]. Side effects include tasks like [[data fetching]], [[DOM manipulation]], subscriptions, and timers — operations that occur _outside_ the normal rendering process.

The `useEffect` hook runs after the component renders. You can control _when_ it runs by specifying a **dependency array**.

Example:

```js
useEffect(() => {
  // Runs on mount
  fetchData();
}, []); // empty array = run only once
```

Common use cases:

- [[data fetching]]
    
- Listening to events
    
- Cleaning up resources (e.g., with `return`)
    

Proper use of `useEffect` is crucial for managing [[component lifecycle]] behavior in [[React]] functional [[components]].
