The **Context API** is a built-in feature in [[React]] that allows for the sharing of [[state]] and values across [[components]] without the need to manually pass them through multiple layers via [[props]] (a problem known as **prop drilling**).

Context is ideal for **global** or **[[shared state]]**, such as theme settings, user authentication, or language preferences.

Basic flow:

1. Create a context with `React.createContext()`
    
2. Wrap your component tree with a `Context.Provider`
    
3. Access the context inside any [[child component]] using `useContext`
    

The Context API simplifies [[data flow]] in medium-sized applications and is a lightweight alternative to external [[tooling|tools]] like [[Redux]] for simple use cases.