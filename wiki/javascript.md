# JavaScript

* https://developer.mozilla.org/pt-BR/docs/Web/JavaScript

# Reestruturando Array

```javascript
var arr = [{key:"11", value:"1100"},{key:"22", value:"2200"}];
var object = arr.reduce(
  (obj, item) => Object.assign(obj, { [item.key]: item.value }), {});

console.log(object)
```
