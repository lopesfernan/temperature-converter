# temperature-converter
Convert temperature between Fahrenheit to Celsius

# Temperature Converter Module
A simple Node.js module for converting temperatures between
Fahrenheit and Celsius.

# Example usage
```js
const { fahrenheitToCelsius, celsiusToFahrenheit }
  = require('@npmlopesfernan/temperature-converter');
const celsius = fahrenheitToCelsius(100);
console.log(`100°F is ${celsius}°C`);
const fahrenheit = celsiusToFahrenheit(37);
console.log(`37°C is ${fahrenheit}°F`);
```

# Running Tests
To run tests and ensure the module is working as expected,
navigate to the module's root directory and execute:
```sh
$ npm run test
```
# License
This project is licensed under the MIT License.