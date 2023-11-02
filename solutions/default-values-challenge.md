# 🧪 Default values (13/10/2023)

```javascript
function createPikachu({ size = 1, power = 250 }) {
    return { name: 'Pikachu', size, power };
}

const p = createPikachu();
console.log(p);
```

### ✅ Solution
The expected output is: `TypeError: Cannot read properties of undefined (reading 'size')`

### 📝 Explanation
The output is TypeError as there is an error in the code. It's subtle but important.

The problem is that although it looks like we are passing default values, in reality the function receives an object, so for it to be correct we should do it in one of two ways:

```javascript
function createPikachu({ size = 1, power = 250 } = {}) {
    return { name: 'Pikachu', size, power };
}

//or

createPikachu({})
```

[⬅️ back](../README.md#default-values-13102023)