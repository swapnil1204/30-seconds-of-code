---
title: arrayWithUniqueElement convert to array which has unique element( reduce duplicate element)
tags: array
---

Convert given array which has duplicate elements to unique array which has only unique element.

- Use `new Set()` to create an set.

```js
    function arrayWithuniqueElement( arrayWithDuplicateElement ){
        return [... new Set( arrayWithDuplicateElement )];
    }
    
    arrayWithuniqueElement([14,28,94,26,14,85,26])  //  [14, 28, 94, 26, 85]
```
