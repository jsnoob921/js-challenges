# js-challenges

This repository hosts all the code challenges that are shared on my twitter profile

<a href="https://img.shields.io/twitter/follow/_jsnoob?style=for-the-badge&color=blue">
    <img src="https://img.shields.io/twitter/follow/_jsnoob?style=social&logo=twitter"
        alt="follow on Twitter">
</a>

<br />

The challenges are sorted chronologically and have their respective solutions/explanations.

## 🧪 Challenges

- [forEach loop challenge](#🧪-foreach-challenge-03102023)

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
