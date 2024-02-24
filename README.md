# Investment Calculator: Buf Fixing

The calculator that dynamically calculates investment values based on your input. A user can specify an initial investment, annual additional investment, annual interest rate, and the duration of the investment in years. The app outputs the table in which each row includes the year of the investment, total value of the investment, interest earned during this year, total interest earned, and total invested capital.

This project covered all the React essentials for building an interactive web application.

## Important note

This project represents the same app and, fundamentally, same code as the project "Investment Calculator" https://github.com/Zhemchuzhnykov/investment-calculator. The only difference is that, in this project, bugs were artificially created for practicing the skills of debugging, finding errors, and bug fixing. The skillset practiced in this project and real bug scenarios are described below.

## Concepts Learned During This Project

- Making sense of React error messages
- Finding logical errors via the browser DevTools & Debugger
- Placing a break point in the DevTools and debugging an app
- Enabling React's strict mode and understanding React's strict mode
- Using the extension React DevTools for application analysis & manipulation

### Appendix 1: Bug Scenarios

1. Execution error: The app crashes when, in the field of the investment duration, a user inputs either 0, or a negative number.
2. Logical error: When a certain number, for example 15000, is input, the results are produced with the long float numbers, for example $150,002,100,900,132,690,001,260,541,280, and NaN.
