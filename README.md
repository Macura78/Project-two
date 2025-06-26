/*
Project Summary

This project is a simple C++ investment calculator that helps users visualize the future value of an investment over time, with or without additional monthly deposits. By allowing inputs for initial investment, monthly deposits, annual interest rate, and the number of years, the program computes and displays annual balances and interest earned, both with and without monthly contributions. The goal is to provide users with financial insight and better decision-making tools regarding their investments.

What I Did Well

I implemented the core financial formulas accurately and created two distinct output formats that help users compare results with and without monthly contributions. The program effectively handles user input, performs compound interest calculations, and displays data in a clean, readable format.

Potential Code Enhancements

Some improvements could include:
- Input validation: Ensuring that negative or non-numeric values do not break the program.
- Refactoring for reusability: Extracting shared logic (e.g., interest calculation) into reusable functions could reduce duplication.
- Adding unit tests: Incorporating a test suite would help validate future changes and enhance reliability.
These improvements would increase the program's robustness, user-friendliness, and maintainability.

Most Challenging Code and How I Overcame It

The most challenging aspect was implementing the correct interest calculation in the displayWithMonthlyDeposits function, which required iterating through each month, applying monthly deposits and compounding the interest monthly. I reviewed multiple compound interest formulas and used online C++ syntax documentation and examples to ensure the calculations were accurate.

Transferable Skills

This project strengthened several transferable skills:
- Working with loops and conditionals
- Understanding and implementing compound interest
- Formatted output using iomanip
- User input handling
These skills are directly applicable in future coursework related to finance, data structures, and software development.

Code Maintainability, Readability, and Adaptability

To keep the program maintainable:
- I used descriptive function names to clearly separate functionality.
- Indentation and whitespace were consistently applied for readability.
- Constants and variables were named meaningfully to reflect their purpose.
To improve adaptability, functions can easily be extended or modified for more complex investment scenarios, such as varying interest rates or inflation factors.
*/
