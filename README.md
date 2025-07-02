# CLI-Based Calculator

## mtalha_cli_calculator
A simple and interactive command-line calculator built with Node.js and TypeScript.

## Features

*   Interactive prompts for choosing operations (Addition, Subtraction, Multiplication, Division) and inputting numbers.
*   Supports the four basic arithmetic operations.
*   Utilizes colorful and animated terminal output for a better user experience.
*   Allows users to perform multiple calculations in a single session.
*   Clear ASCII art representation of a calculator.

## Technologies Used

*   Node.js
*   TypeScript
*   [inquirer](https://www.npmjs.com/package/inquirer) - For interactive command-line prompts.
*   [chalk](https://www.npmjs.com/package/chalk) - For terminal string styling.
*   [chalk-animation](https://www.npmjs.com/package/chalk-animation) - For terminal animations.

## Installation

To use this calculator, you need to have Node.js and npm (Node Package Manager) installed on your system.

You can install the calculator globally using npm:

```bash
npm install -g mtalha_cli_calculator
```

This will make the `mtalha_cli_calculator` command available in your terminal.

### For Development (Optional)

If you want to contribute or run the project locally:

1.  Clone the repository:
    ```bash
    git clone <repository_url> # Replace <repository_url> with the actual URL
    cd mtalha_cli_calculator
    ```
2.  Install dependencies:
    ```bash
    npm install
    ```
3.  Compile TypeScript to JavaScript (as `index.js` is the main file specified in `package.json`):
    ```bash
    npx tsc
    ```
    (Alternatively, you can run the TypeScript file directly using `ts-node` if you have it installed: `npx ts-node index.ts`)


## Usage

Once installed globally, you can run the calculator by simply typing the following command in your terminal:

```bash
mtalha_cli_calculator
```

The application will then guide you through:
1.  A welcome message.
2.  Prompting you to select an arithmetic operation.
3.  Prompting you to enter the first number.
4.  Prompting you to enter the second number.
5.  Displaying the result.
6.  Asking if you wish to perform another calculation.

## Author

Developed by: **Muhammad Talha Tariq**
PIAIC 234119 Badge: 52. Lahore, Pakistan.

## License

This project is licensed under the ISC License. (See `package.json` for details).
