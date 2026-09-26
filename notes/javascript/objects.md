# Topic: Objects and Arrays
**Date:** 2026-sep-25
**Phase:** Phase 1 — JavaScript
**Status:** 🟠learning 

## What I learned
- `arrays` - is an ordered list wrapped in square brackets "[...]"
  - each item has a position number, the first item starts     at `0` no `1`
- `length` - how many items that are in the index
- `Object` - An object groups values with lables(keys)        wrapped with curley brackets "{...}"
  - Each entry is a key paired with a value 
  - When acessing/ calling values: use dot notation ( consolelog.(person.name))
  - Order doesn't matter , lables do, you just call `person.name`


## Code snippet / demo

### Array of colors

```js
let colors = ["red", "green", "blue"]
let numbers = [1, 2, 3, 4, 5]
let mixed = ["Alice", 30, true]
```

###  Array Index number positions
```js
let colors = ["red", "green", "blue"]
//               0      1       2

console.log(colors[0])     //square brackets + number prints item
console.log(colors[1])
console.log(colors[2])
```
### Objects - labeled values

```js
let person = {
  name: "Alice"                // each entry has key: value pair
  age: 30,
  isReady: true
}

console.log(person.name)      // "Alice"
console.log(person.age)       // 30
console.log(person.isReady)   // true
```

### `.length`: print how many items
```js
console.log(colors.length)    // 3
```

### Array of objects 
```js
let people = [
  { name: "Alice" age: 30 },
  { name: "Bob", age: 25 },
  { name: "Charlie", age: 35 }
]
```
### Looping through them
```js
for (let i = 0; i < people.length; i++) {
  console.log(people[i].name)
}

```

## Gotchas / mistakes
- Arrays start at 0, not 1. 
- Dot vs Brackets for objects
    ```js
  person.name         // ✅ dot — when you know the key
person["name"]      // ✅ bracket — also works
person.name2        // undefined — key doesn't exist (no error!)
    ```
- In `for` loop use `;`
   ```js
   for ( let i = 0; i x.length; i++)
   ```

## Resources used
- Deepseek chat
- Youtube - Learn JavaScript in 60 Minutes: The Ultimate Beginner Course!

## Next steps
- Unite 6: Console Calculator
