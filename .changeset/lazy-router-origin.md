---
'@lit-labs/router': patch
---

Read `location.origin` lazily so `@lit-labs/router` can be imported in Node (for example during SSR) without throwing `ReferenceError: location is not defined`.
