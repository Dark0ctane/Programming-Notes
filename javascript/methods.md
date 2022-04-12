### reduce()

```
let array = [1, 2, 3, 4, 5, 6, 1, 3, 1, 1];

let sumArray = array.reduce((prevValue, currValue) => {
  return prevValue + currValue;
})
```

* Adds previous item in the array with the next using a callback function for each item
