
When starting a new [[React]] project, there are several options for how to **set up the development environment**, depending on the goals (learning vs production).

---

### 🧱 [[Create-React-App (CRA)]]

- A **starter kit** for React apps created years ago to simplify setup.
    
- Preconfigures tools like:
    
    - `webpack` (for [[bundling|bundling]]) [[Webpack]]
        
    - `ESLint` ([[linting]]) [[ESLint]] 
        
    - `Prettier` (code formatting) [[Prettier]]
        
    - `Jest` (testing) [[Jest]]
        
    - `Babel` (modern JavaScript) [[babel]]
        
- ❗ CRA is **considered outdated** for production use because of slower performance and lack of innovation.
    
- ✅ Still **ideal for learning**, tutorials, and quick prototypes.
    

---

### ⚡ [[Vite]]

- A **modern build [[tooling|tool]]** — faster than CRA and uses native [[ES modules|ES modules]].
    
- Offers:
    
    - **[[Hot Module Replacement (HMR)]]**
        
    - Extremely fast [[bundling|bundling]] and page refresh
        
    
- 🧠 Better choice for **real-world apps** and [[large-scale projects]].
    

---

### 🧠 When to Use Each:

|Purpose|Use|
|---|---|
|Learning, tutorials|CRA|
|Real projects|Vite|

---

### 📦 React [[Frameworks]] (e.g., [[Next.js]], [[Remix]])

- [[React]] itself is a **UI [[libraries|library]]**, not a full framework.
    
- [[Frameworks]] like [[Next.js]] and [[Remix]] add:
    
    - [[Routing]]
        
    - [[Data fetching]]
        
    - [[Server-side rendering (SSR)]]
        
- ⚠️ These are **not required for learning React** and are better suited for **production-ready apps**.
    
- Don’t start with frameworks unless you already understand the core of React.
    

---

**Summary:**  
Start learning React using [[Create-React-App (CRA)|Create-React-App]] to focus on the fundamentals without worrying about tooling. Move to [[Vite]] for more realistic, faster builds later. Ignore the push toward frameworks like [[Next.js]] until you’re confident in **vanilla React**.
