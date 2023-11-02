# JS Challenges

<p align="center">
    <a href="https://img.shields.io/twitter/follow/_jsnoob?style=for-the-badge&color=blue">
        <img src="https://img.shields.io/twitter/follow/_jsnoob?style=social&logo=twitter"
            alt="follow on Twitter">
    </a>
    &nbsp;
    <a href="https://img.shields.io/github/license/jsnoob921/js-challenges">
        <img src="https://img.shields.io/github/license/jsnoob921/js-challenges" alt="License">
    </a>
</p>

<br />

This repository hosts all the code challenges that are shared on my twitter profile

The challenges are sorted chronologically and have their respective solutions/explanations.

<h2 align=center>📝 How to Contribute?</h2>

Contributions in any programming language are welcome. But first of all, please have a look at the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## <h2 align=center>🧪 Challenges</h2> 

- [forEach loop challenge](#foreach-challenge-03102023)
- [Type coercion challenge (I)](#type-coercion-challenge-i-09102023)
- [Increment operator](#increment-operator-11102023)

### forEach challenge (03/10/2023)

```javascript
const numbers = [1, 2, 3, 4, 5];
const squares = [];

numbers.forEach((num, index, what) => {
    what[index] = num * num;
});

console.log(numbers);
```

[✅ solution](./solutions/forEach-challenge.md)

### Type coercion challenge (I) (09/10/2023)

```javascript
const isTrue = true == [];
const isFalse = true == ![];

console.log(isTrue + isFalse);
```

[✅ solution](./solutions/type-coercion-I.md)

### Increment operator challenge (11/10/2023)

```javascript
let num = 15;

console.log(num++);
```

[✅ solution](./solutions/increment-operator-challenge.md)

### Default values challenge (13/10/2023)

```javascript
function createPikachu({ size = 1, power = 250 }) {
    return { name: 'Pikachu', size, power };
}

const p = createPikachu();
console.log(p);
```

[✅ solution](./solutions/default-values-challenge.md)

### Asynchronous challenge (I) (16/10/2023)

```javascript
console.log(1);

setTimeout(() => {
    console.log(2);
}, 0);

console.log(3);
```

[✅ solution](./solutions/asynchronous-I.md)