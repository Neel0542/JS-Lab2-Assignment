Lab 2 - JavaScript Frameworks (Node.js & Modules)
This project demonstrates the use of ES Modules in Node.js by creating and using custom utility functions. The goal was to practice importing and exporting modules while implementing functions to perform basic tasks such as unit conversions, mathematical operations, and prime number checks.

Project Structure

Lab2-JS-frameworks/
│── utilities.js   # Contains utility functions
│── index.js       # Main entry point that imports and runs functions
│── README.md      # This file
Key Files:
utilities.js: This file contains all the utility functions that can be reused throughout the project.
index.js: This is the main script that imports functions from utilities.js and demonstrates their functionality.
Functions Implemented
greet(name)

Purpose: Prints a friendly motivational message.
Example: "Hello Group 3! Keep pushing your limits in JavaScript!"
convertKmToMiles(km)
Purpose: Converts a distance in kilometers to miles.
Example: 10 km = 6.21 miles
sumOfSquares(number)
Purpose: Calculates the sum of squares of each digit in the number.
Example: For 123 → 1² + 2² + 3² = 14
isPrime(num)
Purpose: Checks if a given number is prime.
Example:
Is 17 a prime number? → true
Is 20 a prime number? → false
