# Credit Card Validator - Luhn Algorithm

This project demonstrates the implementation of the Luhn algorithm (also known as the "modulus 10" algorithm) to validate credit card numbers. Built as part of my JavaScript learning journey with Codecademy guidance.

## How It Works

The Luhn algorithm validates credit card numbers through a mathematical checksum:

1. Starting from the rightmost digit, double every second digit
2. If doubling results in a two-digit number, add the digits together
3. Sum all the digits
4. If the total is divisible by 10, the number is valid

## Usage

```javascript
// Example usage
const cardNumber = "4532015112830366";
const isValid = validateCard(cardNumber);
console.log(isValid); // true or false
```

## Technologies Used

- **JavaScript (ES6+)** - Core implementation
- **HTML5** - User interface structure  
- **CSS3** - Styling and layout

## Learning Outcomes

This project helped me:
- Algorithm implementation in JavaScript
- Mathematical operations and modular arithmetic
- Input validation and error handling
- Code organization and best practices
- Financial technology concepts

Built with ❤️ as part of my Computer Science journey | [Portfolio](https://theotherflaneur.vercel.app/)
