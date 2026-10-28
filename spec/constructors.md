There are few types of data:

1. Literal
2. Struct
3. Array

# Literal

```
// unit
() = [x, 0]

// integer
10

// float
3.14

// string
"value"

// char (special case of a string)
"r"
```

## Example

```
"some text..."
```

# Struct
```
(x, y)
```

There is no difference between structs and tuples. You might call tuples with named fields structs and tuples without named fields tuples, but one tuple/struct may contain some named fields and some unnamed fields and it is perfectly correct:
```
(x: 10, 343)
```

## Example

```
("Hello, ", "World!) = "Hello, World!"

("My age is: ", 20) = ("My age is: ", 20)
```

# Array
Array enclosed in `[]` and has only two elements:
1. Data
2. Length

Array represents `x` repeated `n` times.

```
[x, n]
```

## Example

```
// "hello hello "
["hello ", 2]
```
