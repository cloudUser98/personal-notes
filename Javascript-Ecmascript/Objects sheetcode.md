# Notes about objects

## Methods

### Object.prototype.group()
Groups the objects of an iterable by passing a callback function that returns
the string value used for the grouping.

```javascript
const iterable = [
    { label: "products", value: "salt" },
    { label: "products", value: "pepper" },
    { label: "resources", value: "water" }
]

// Grouping objects by the label
const result = Object.groupBy(iterable, ({ label }) => label)

/* Result:
    {
        products: [
            { label: "products", value: "salt" },
            { label: "products", value: "pepper" }
        ],
        resources: [
            { label: "resources", value: "water" }
        ]
    }
*/
```

> Note: In some versions of some browsers, this method was implemented as the 
method Array.prototype.group(). Due to web compatibility issues, it is now 
implemented as a static method. - MDN Web Docs
