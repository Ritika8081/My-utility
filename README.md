# My-utility
My NPM Package 
**My Utility** is a collection of utility functions designed to streamline common coding tasks. Whether you're working with strings, performing data validation, or formatting dates and times, this package provides handy functions to make your life easier.


## Installation

You can install My Utils via npm:

```bash
npm i my-utility
```
Usage
Once installed, you can import and use the utility functions in your JavaScript projects:

```

const {
  capitalizeFirstLetter,
  isValidEmail,
  formatDate,
  generateRandomString,
  isValidUrl,
  shuffleArray,
  factorial,
  getRandomInt
} = require('your-package-name');

// Example usage of the functions

// Capitalize the first letter of a string
const capitalizedString = capitalizeFirstLetter('hello');

// Check if an email address is valid
const isValid = isValidEmail('test@example.com');

// Format the current date
const formattedDate = formatDate(new Date());

// Generate a random alphanumeric string of length 10
const randomString = generateRandomString(10);

// Check if a URL is valid
const isValidURL = isValidUrl('https://example.com');

// Shuffle an array
const shuffledArray = shuffleArray([1, 2, 3, 4, 5]);

// Calculate the factorial of 5
const factorialValue = factorial(5);

// Generate a random integer between 1 and 100
const randomInt = getRandomInt(1, 100);


```
 ## Features

 `capitalizeFirstLetter`: Capitalizes the first letter of a string.
- `isValidEmail`: Checks if a string is a valid email address.
- `formatDate`: Formats a Date object as "YYYY-MM-DD".
- `generateRandomString`: Generates a random alphanumeric string of a specified length.
- `isValidUrl`: Checks if a string is a valid URL.
- `shuffleArray`: Shuffles the elements of an array.
- `factorial`: Calculates the factorial of a number.
- `getRandomInt`: Generates a random integer within a specified range.


## How It Helps

`Saves Time:` Instead of writing these utility functions from scratch, you can simply install My Utils and start using them immediately, saving you time and effort.
`Improves Code Quality:` By using standardized utility functions, you can ensure consistency across your codebase and reduce the likelihood of errors.
`Enhances Readability:` The descriptive function names and clear documentation make it easy for you and your team to understand and use these utilities effectively.
Contribution

`Contributions are welcome! If you have ideas for additional utility functions or improvements to existing ones, please open an issue or submit a pull request on GitHub.`

## License
This package is licensed under the MIT License. See the LICENSE file for details.

Author 
## Ritika Mishra


