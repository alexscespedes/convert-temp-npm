# Temperature Converter GPT

This package allows you to convert temperatures between Celsius and Fahrenheit.
(Provided by ChatGPT)


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)

## Installation

```bash
npm install convert-temp-npm
```

## Usage

```javascript
const { celsiusToFahrenheit, fahrenheitToCelsius } = require('convert-temp-npm');

const celsius = 30;
const fahrenheit = celsiusToFahrenheit(celsius);
console.log(`${celsius} grados Celsius son ${fahrenheit} grados Fahrenheit.`);

const newCelsius = fahrenheitToCelsius(fahrenheit);
console.log(`${fahrenheit} grados Fahrenheit son ${newCelsius} grados Celsius.`);
```