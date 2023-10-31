# 🧪 forEach challenge (03/10/2023)

```javascript
const numbers = [1, 2, 3, 4, 5];
const squares = [];

numbers.forEach((num, index, what) => {
    what[index] = num * num;
});

console.log(numbers);
```

### ✅ Solution
The expected output is: `[1, 4, 9, 16, 25]`. 

### 📝 Explanation
The third parameter of the `forEach` callback is the array being iterated. Therefore, we can modify it. In this case, we are modifying the array numbers inside the callback.

[⬅️ back](../README.md#foreach-challenge-03102023)