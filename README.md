# My-utility
My NPM Package 
( My Utility ) is a collection of utility functions designed to streamline common coding tasks. Whether you're working with strings, performing data validation, or formatting dates and times, this package provides handy functions to make your life easier.

## Installation

You can install My Utils via npm:

```bash
npm i my-utility
```
Usage
Once installed, you can import and use the utility functions in your JavaScript projects:

```

const { capitalizeFirstLetter, isValidEmail, formatDate } = require('my-utils');

// Capitalize the first letter of a string
console.log(capitalizeFirstLetter('hello')); // Output: Hello

// Check if an email address is valid
const email = 'test@example.com';
console.log(isValidEmail(email)); // Output: true

// Format the current date as "YYYY-MM-DD"
const today = new Date();
console.log(formatDate(today)); // Output: "2024-03-04"

```
 ## Features

capitalizeFirstLetter(string)

Capitalizes the first letter of a string.

isValidEmail(email)

Checks if a string is a valid email address.

formatDate(date)

Formats a Date object as "YYYY-MM-DD".

## How It Helps

 ## Saves Time:

Instead of writing these utility functions from scratch, you can simply install My Utils and start using them immediately, saving you time and effort.
Improves Code Quality: By using standardized utility functions, you can ensure consistency across your codebase and reduce the likelihood of errors.
Enhances Readability: The descriptive function names and clear documentation make it easy for you and your team to understand and use these utilities effectively.
Contribution
Contributions are welcome! If you have ideas for additional utility functions or improvements to existing ones, please open an issue or submit a pull request on GitHub.

## License
This package is licensed under the MIT License. See the LICENSE file for details.

Author 
## Ritika Mishra


