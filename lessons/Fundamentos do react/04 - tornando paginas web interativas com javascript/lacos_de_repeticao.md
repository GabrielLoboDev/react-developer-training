# Laços de repetições
Laços em JavaScript (ou loops) são uma maneira eficaz de se trabalhar com estruturas de repetições baseadas em estruturas condicionais dentro da linguagem, ao invés de repetir milhares de vezes determinado código, pode utilziar os laços para repetir qualquer coisa até que qualquer outra coisa aconteça.

## Laços de repetições
- for
- while
- foreach
- map

## for
```javascript
    for (let i = 0; i < 10; i++) {
        console.log(i);
    };
```

## while
```javascript
    let counter = 1;

    while (counter < 10) {
        console.log(counter);
        counter++;
    };
```

## foreach
```javascript
    const numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

    numbers.forEach((value) => {
        console.log(value);
    });
```

## map
```javascript
    const letters = ["A", "B", "C", "D", "E"];

    const lowerLetters = letters.map((letter) => {
        return letter.toLowerCase();
    });
```