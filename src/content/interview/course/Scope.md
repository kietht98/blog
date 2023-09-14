---
title: "Scope"
description: "Nested (child) function have access to the scope of their parent functions"
pubDate: "Jul 08 2022"
heroImage: "/blog-placeholder-3.jpg"
---

\ # Scope

- Lexical Scope

- Nested (child) function have access to the scope of their parent functions

- Global scope

- Immediately Invoked Function Expression

```
const privateCounter = (() => {
let count = 0;
console.log(`initial values: ${count}`);
return () => {count +=1; console.log(count)}
})();
```
