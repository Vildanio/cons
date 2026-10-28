# Bindings
Bindings are key-value pairs.
Note that bindings do not introduce scopes and it is not correct to "refer" to a binding. It is purely a comment at this point.

## Example

```
pi: 3.14

greeting: "Hello, World!"
```

### Structs

```
point: (
  x: 10,
  y: 10,
)
```

Nested structs:
```
user: (
  name: "Ivan",
  insurance: (
    id: "Don't know",
    company: "Don't know",
  )
)
```

### Arrays

```
data: [
  i: 5,
  n: 100
]
```
