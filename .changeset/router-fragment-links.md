---
'@lit-labs/router': patch
---

`Router` no longer intercepts links to a fragment of the current page (like `href="#section"`), so the browser scrolls to the target.
