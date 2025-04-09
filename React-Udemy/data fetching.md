**[[Data]] fetching** refers to the process of retrieving external [[data]] — usually from an [[APIs|API]] — to be used in a [[frontend]] [[εφαρμογή]]. It is a core part of building dynamic web apps, where content is not hardcoded but loaded based on user interaction or [[εφαρμογή]] [[state]].

In [[JavaScript]], common tools for [[data]] fetching include:

- `fetch` API (built-in) [[fetch API]]
    
- `Axios` (third-party library)[[Axios]]
    
- `GraphQL clients` (e.g., Apollo)
    

In [[React]], [[data]] fetching is often performed inside the `useEffect` hook to trigger side effects after rendering.


`useEffect(() => {   fetch('/api/user')     .then(res => res.json())     .then(data => setUser(data)); }, []);`
[[useEffect]]
Proper handling includes managing **loading states**, **error handling**, and sometimes **caching** or **pagination**.