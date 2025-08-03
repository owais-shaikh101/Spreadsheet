## Functional Programming Spreadsheet

This project is a lightweight, browser-based spreadsheet application built with HTML, CSS, and vanilla JavaScript. It showcases the power and flexibility of functional programming by implementing formula parsing, range expansion, and a suite of spreadsheet-like functions, all without the use of external libraries.

### Features

- **Grid Layout**: A responsive 10-column by 99-row spreadsheet grid, dynamically generated.
- **Cell Input Evaluation**: Supports expressions beginning with `=`, evaluated recursively using custom logic.
- **Mathematical Expression Parsing**: Handles operator precedence (multiplication/division before addition/subtraction).
- **Functional Utilities**: Includes common spreadsheet functions such as:
  - `sum()`, `average()`, `median()`
  - Filters like `even()`, `someeven()`, `everyeven()`
  - Range manipulation with `firsttwo()`, `lasttwo()`, `range()`
  - Other utilities like `increment()`, `random()`, `nodupes()`, and more.
- **Cell Referencing & Ranges**: Supports expressions referencing other cells and ranges (e.g. `A1:B2`).
- **Recursive Evaluation**: Resolves nested or chained formula evaluations.

This project is ideal for educational purposes, demonstrating how core spreadsheet logic can be implemented with functional programming techniques.
