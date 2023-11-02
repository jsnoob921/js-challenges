# 🧪 Type coercion challenge (I) (09/10/2023)

```javascript
const isTrue = true == [];
const isFalse = true == ![];

console.log(isTrue + isFalse);
```

### ✅ Solution
The expected output is `0`.

### 📝 Explanation
The result of both comparisons (`true == []` and `true == ![]`) is false. Therefore, when we add two falsy values together, they are evaluated as 0, so if we add 0 to 0, the result is 0.

[⬅️ back](../README.md#type-coercion-challenge-i-09102023)