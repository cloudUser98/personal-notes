# Is JS object desctructuring bad?
```javascript
const values = Array(1000)
    .fill(0)
    .map((_, i) => i);

const valueObject = ... 8: 88, 89:
    values.reduce((acc, value) => ({
        ...acc,
       [value]: value,
    }), {});
```

Tags:
  Javascript