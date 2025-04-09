**Callbacks** are **[[functions]] passed as arguments** to other [[functions]], allowing custom logic to be executed after a certain task completes. In [[JavaScript]], callbacks are commonly used in **[[asynchronous]]** operations, like timers, event handling, or [[data fetching]].

Example:
`setTimeout(() => {   console.log("This runs after 2 seconds"); }, 2000);`

Before the introduction of [[promises]] and `async/await`, callbacks were the main way to handle [[asynchronous]] code — but they often led to **callback hell**, a situation where [[functions]] are nested within [[functions]], making code [[hard to read]] and [[Συντήρηση]].

Callbacks are still useful in synchronous logic (e.g., [[array methods]] like `.map()`, `.filter()`) and for customizing behaviors.