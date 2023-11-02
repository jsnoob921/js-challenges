# 🧪 Asynchronous loop challenge (20/10/2023)

```javascript
for (var i = 0; i < 3; i++) {
    setTimeout(() => console.log(i), 1);
}

for (let i = 0; i < 3; i++) {
    setTimeout(() => console.log(i), 1);
}
```

### ✅ Solution
The expected output is `3 3 3` and `0 1 2`.

### 📝 Explanation
In the first loop we are using `var` and in the second loop we are using `let`. 


`var` has a function scope and `let` has a block scope defined by braces.

As the `setTimeout` is executed after the loop has been fully executed, when the callback of `setTimeout` is executed in the first loop, the value of i is 3. In the second loop, as `let` has a block scope, the value of i is as expected.

[⬅️ back](../README.md#asynchronous-loop-challenge-20102023)