# Functions
De modo geral, função é um "subprograma" que pode ser chamado por código externo (ou interno no caso de recursão) à função. Assim como o programa em si, uma função é composta por uma sequência de instruções chamada corpo da função. Valores podem ser passados para uma função e ela vai retornar um valor.

## Estrutura de uma função
```javascript
    function sum(num1, num2) {
        return num1 + num 2;
    };
```

## Arrow Functions
A versão do ECMA Script 2015 do JavaScript, trouxe uma nova forma mais sucinta de trabalhar com funções chamada de Arrow Functions, por causa da sintaxe que lembra uma flecha:
```javascript
    () =>
```
```javascript
    const sum = (num1, num2) => {
        return num1 + num2;
    };
```

## Exemplo básico de uso de uma arrow function
```javascript
    // "return" is not necessary.
    const sum = (num1, num2) => num1 + num2;
```