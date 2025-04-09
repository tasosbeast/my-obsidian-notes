
**Promises** in **[[JavaScript]]** are a way to handle **[[asynchronous]]** operations. A promise represents a value that may be available now, in the future, or never. It allows developers to write cleaner, more readable [[asynchronous]] code compared to traditional [[callbacks]].

A promise has three states:

- **Pending** – the operation is ongoing
    
- **Fulfilled** – the operation completed successfully
    
- **Rejected** – the operation failed
    

Example:

```js
fetch('/api/data')
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.error(error));
```

Promises are often used when working with [[APIs]], [[data fetching]], or any [[asynchronous]] logic. They are also the foundation of `async/await` syntax introduced in ES2017.