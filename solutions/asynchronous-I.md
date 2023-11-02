# 🧪 Asynchronous challenge (I) (16/10/2023)

```javascript
console.log(1);

setTimeout(() => {
    console.log(2);
}, 0);

console.log(3);
```

### ✅ Solution
The expected output is `1, 3, 2`.

### 📝 Explanation
Since `setTimeout` with a delay of 0 still pushes its callback to the even loop, the third `console.log` will be printed first, followed by `console.log` defined in the `setTimeout` callback.

[⬅️ back](../README.md#asynchronous-challenge-i-16102023)