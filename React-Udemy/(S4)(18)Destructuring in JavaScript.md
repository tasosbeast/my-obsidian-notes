
**Destructuring** is a [[JavaScript]] feature that allows developers to **extract values from [[objects]] or [[arrays]]** into distinct variables in a concise way.

---

### 🔧 Object Destructuring

Used to extract properties from an [[objects|object]] using the property names.

```js
const book = getBook(2); // example book object

// Traditional way:
const title = book.title;
const author = book.author;

// Destructured:
const { title, author } = book;
```

⚠️ The variable names **must match** the object’s property names exactly. For example, `titles` (plural) would result in `undefined` if the actual property is `title`.

Destructuring is especially useful when:

- Accessing multiple properties from an object
    
- Working with [[APIs|API]] responses (like `getBook()` simulating an API)
    

You can also extract multiple properties:

```js
const { title, author, pages, publicationDate, genres, hasMovieAdaptation } = book;
```

---

### 🔧 Array Destructuring

Used to extract values based on **position** in the array, not property names.

```js
const genres = book.genres;

// Traditional way:
const primaryGenre = genres[0];
const secondaryGenre = genres[1];

// Destructured:
const [primaryGenre, secondaryGenre] = genres;
```

This is helpful when:

- The array order is meaningful (e.g., ranked [[data]])
    
- You only care about the first few items
    

---

### 🛠 Tools Mentioned

- **[[Quokka.js]]**: A [[VS Code]] extension that runs [[JavaScript]] inline without needing an [[HTML]] file.
    
- **[[Snippets]]**: Used to quickly write `console.log()` and other boilerplate.
    

---

**Summary:**

Destructuring is a clean and powerful syntax in [[JavaScript]] that improves [[readability]] and reduces code duplication. It's commonly used when dealing with [[objects]] from [[functions]], [[APIs]], or large [[arrays]].
