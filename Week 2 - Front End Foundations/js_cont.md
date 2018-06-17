---
class: middle
## Refactoring + JS Methods

- Let’s rewrite our code to use our array of bands.

- Delete the If / Else statement.

- Rewrite it using our `bands` array and `indexOf()`

---
class: middle
## JS Objects

```JavaScript
var josuesCar = {
    make: "Scion",
    model: "xB",
    year: 2006,
    color: "black",
    run: function() {
        console.log('Vroom vroom!');
    }
}
```
---
class: middle
## JS Object Exercise

- Create an object of your car or dream car
- Tell us the make, model, year, color, years owned, 2 functions: run, stop
- Using dot notation, log out the same information onto the console



class: middle

# Hoisting

> Function declarations are hoisted over variable declarations but not over
> variable assignments.

```javascript
var double;

function double(num) {
  return num * 2;
}

console.log(typeof double); // Output type: ?
```

---

class: middle

# JS ES 2015

```javascript
let x = myFunction(4, 3);

let myFunction = (a, b) => a * b;

function sameFunction(a, b) {
  return a * b;
}
```

---
