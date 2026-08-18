# Funcionalidades do ES6+
- filter
- find
- findIndex
- reduce
- some
- every

## filter
```javascript
    const filteredCars = cars.filter(car => car.age >= 1990);
```
## find
```javascript
    const specificCar = cars.find(car => car.model => "207");
```
## findIndex
```javascript
    // Return the index.
    const index = cars.findIndex(car => car.model => "Ônix");
```
## reduce
```javascript
    const totalValueInInventory = cars.reduce((acc, car) => {
        return acc + car.value;
    }, 0);
```
## some
```javascript
    const greaterThanFive = numbers.some(numbers => numbers < 10);
```
## every
```javascript
    const lessThanEight = numbers.every(numbers => numbers < 8);
```