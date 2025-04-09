
**Objects** in **[[JavaScript]]** are collections of key-value pairs used to group related [[data]] and functionality. Keys (also called **properties**) are typically strings, and values can be any [[data]] type — including other objects or [[functions]] (called **[[methods]]**).

Objects are foundational in [[JavaScript]] and used for:

- Modeling real-world entities
    
- Structuring [[data]]
    
- Organizing [[functions]] and logic
    
- Implementing concepts like **encapsulation** and **[[modularity]]**
    

Example:

```js
const user = {
  name: "Tasos",
  age: 28,
  greet() {
    console.log(`Hello, my name is ${this.name}`);
  }
};
```

Objects are central to both the **[[object-oriented]]** and **[[prototype-based]]** nature of [[JavaScript]].
