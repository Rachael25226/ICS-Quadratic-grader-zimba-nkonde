# ICT251: Single-File Web Application - Quadratic Solver and Grade Converter

This repository contains a **single-file web application (index.html)**
designed to fulfill the ICT251 assignment requirements using HTML, CSS,
and Vanilla JavaScript.

The application serves as a standalone tool providing two distinct
mathematical and academic functionalities.

## Application Features

The single file implements two main features, complete with input
validation and clear output:

### 1. Quadratic Equation Solver {#quadratic-equation-solver}

- **Purpose:** Calculates the discriminant, determines the nature of the
  > roots, and solves the quadratic equation in the form\$\$ax\^2 + bx +
  > c = 0\$\$  
  > .

- **Validation:** Includes checks to ensure all coefficients are numbers
  > and that the leading coefficient, \$a\$, is not equal to zero.

- **Root Handling:** Successfully handles cases resulting in Two
  > Distinct Real Roots (\$\Delta \> 0\$), One Repeated Real Root
  > (\$\Delta = 0\$), and Two Complex Conjugate Roots (\$\Delta \< 0\$).

### 2. Grade Converter {#grade-converter}

- **Purpose:** Converts a numeric score (0-100) to a letter grade based
  > on the defined grading scale.

## Grading Scale

The following criteria are used for the Grade Converter:

| **Grade** | **Score Range** |
|-----------|-----------------|
| **A+**    | **\>= 86**      |
| **A**     | 75 - 85         |
| **B+**    | 65 - 74         |
| **B**     | 60 - 64         |
| **C+**    | 55 - 59         |
| **C**     | 50 - 54         |
| **D+**    | 45 - 49         |
| **D**     | 0 - 44          |

## How to Run the Application

The application is a standalone web page and requires no server
configuration.

1.  **Locate the index.html file.**

2.  **Double-click** the file to open it directly in any modern web
    > browser (Chrome, Firefox, Edge, etc.).

3.  Inputs and results will be displayed in the browser window.

## Test Cases

The following test cases should be used to verify the correct operation
of both functions:

### Quadratic Solver Test Cases

| **Case**            | **a** | **b** | **c** | **Expected Result**         |
|---------------------|-------|-------|-------|-----------------------------|
| 1\. Two Real Roots  | 1     | -3    | 2     | Roots: 2 and 1              |
| 2\. One Real Root   | 1     | -4    | 4     | Root: 2 (Repeated)          |
| 3\. Complex Roots   | 1     | 2     | 5     | Complex Conjugate Roots     |
| 4\. \$a = 0\$ Error | 0     | 5     | 1     | Error: \$a\$ cannot be zero |

### Grade Converter Test Cases

| **Case**          | **Score** | **Expected Grade**                |
|-------------------|-----------|-----------------------------------|
| 1\. A+            | 90        | A+                                |
| 2\. A             | 75        | A                                 |
| 3\. C             | 52        | C                                 |
| 4\. D             | 44        | D                                 |
| 5\. Invalid Input | 101       | Error: Score out of range (0-100) |
# ICT251: Single-File Web Application - Quadratic Solver and Grade Converter

This repository contains a **single-file web application (index.html)**
designed to fulfill the ICT251 assignment requirements using HTML, CSS,
and Vanilla JavaScript.

The application serves as a standalone tool providing two distinct
mathematical and academic functionalities.

## Application Features

The single file implements two main features, complete with input
validation and clear output:

### 1. Quadratic Equation Solver {#quadratic-equation-solver}

- **Purpose:** Calculates the discriminant, determines the nature of the
  > roots, and solves the quadratic equation in the form\$\$ax\^2 + bx +
  > c = 0\$\$  
  > .

- **Validation:** Includes checks to ensure all coefficients are numbers
  > and that the leading coefficient, \$a\$, is not equal to zero.

- **Root Handling:** Successfully handles cases resulting in Two
  > Distinct Real Roots (\$\Delta \> 0\$), One Repeated Real Root
  > (\$\Delta = 0\$), and Two Complex Conjugate Roots (\$\Delta \< 0\$).

### 2. Grade Converter {#grade-converter}

- **Purpose:** Converts a numeric score (0-100) to a letter grade based
  > on the defined grading scale.

## Grading Scale

The following criteria are used for the Grade Converter:

| **Grade** | **Score Range** |
|-----------|-----------------|
| **A+**    | **\>= 86**      |
| **A**     | 75 - 85         |
| **B+**    | 65 - 74         |
| **B**     | 60 - 64         |
| **C+**    | 55 - 59         |
| **C**     | 50 - 54         |
| **D+**    | 45 - 49         |
| **D**     | 0 - 44          |

## How to Run the Application

The application is a standalone web page and requires no server
configuration.

1.  **Locate the index.html file.**

2.  **Double-click** the file to open it directly in any modern web
    > browser (Chrome, Firefox, Edge, etc.).

3.  Inputs and results will be displayed in the browser window.

## Test Cases

The following test cases should be used to verify the correct operation
of both functions:

### Quadratic Solver Test Cases

| **Case**            | **a** | **b** | **c** | **Expected Result**         |
|---------------------|-------|-------|-------|-----------------------------|
| 1\. Two Real Roots  | 1     | -3    | 2     | Roots: 2 and 1              |
| 2\. One Real Root   | 1     | -4    | 4     | Root: 2 (Repeated)          |
| 3\. Complex Roots   | 1     | 2     | 5     | Complex Conjugate Roots     |
| 4\. \$a = 0\$ Error | 0     | 5     | 1     | Error: \$a\$ cannot be zero |

### Grade Converter Test Cases

| **Case**          | **Score** | **Expected Grade**                |
|-------------------|-----------|-----------------------------------|
| 1\. A+            | 90        | A+                                |
| 2\. A             | 75        | A                                 |
| 3\. C             | 52        | C                                 |
| 4\. D             | 44        | D                                 |
| 5\. Invalid Input | 101       | Error: Score out of range (0-100) |
# ICT251: Single-File Web Application - Quadratic Solver and Grade Converter

This repository contains a **single-file web application (index.html)**
designed to fulfill the ICT251 assignment requirements using HTML, CSS,
and Vanilla JavaScript.

The application serves as a standalone tool providing two distinct
mathematical and academic functionalities.

## Application Features

The single file implements two main features, complete with input
validation and clear output:

### 1. Quadratic Equation Solver {#quadratic-equation-solver}

- **Purpose:** Calculates the discriminant, determines the nature of the
  > roots, and solves the quadratic equation in the form\$\$ax\^2 + bx +
  > c = 0\$\$  
  > .

- **Validation:** Includes checks to ensure all coefficients are numbers
  > and that the leading coefficient, \$a\$, is not equal to zero.

- **Root Handling:** Successfully handles cases resulting in Two
  > Distinct Real Roots (\$\Delta \> 0\$), One Repeated Real Root
  > (\$\Delta = 0\$), and Two Complex Conjugate Roots (\$\Delta \< 0\$).

### 2. Grade Converter {#grade-converter}

- **Purpose:** Converts a numeric score (0-100) to a letter grade based
  > on the defined grading scale.

## Grading Scale

The following criteria are used for the Grade Converter:

| **Grade** | **Score Range** |
|-----------|-----------------|
| **A+**    | **\>= 86**      |
| **A**     | 75 - 85         |
| **B+**    | 65 - 74         |
| **B**     | 60 - 64         |
| **C+**    | 55 - 59         |
| **C**     | 50 - 54         |
| **D+**    | 45 - 49         |
| **D**     | 0 - 44          |

## How to Run the Application

The application is a standalone web page and requires no server
configuration.

1.  **Locate the index.html file.**

2.  **Double-click** the file to open it directly in any modern web
    > browser (Chrome, Firefox, Edge, etc.).

3.  Inputs and results will be displayed in the browser window.

## Test Cases

The following test cases should be used to verify the correct operation
of both functions:

### Quadratic Solver Test Cases

| **Case**            | **a** | **b** | **c** | **Expected Result**         |
|---------------------|-------|-------|-------|-----------------------------|
| 1\. Two Real Roots  | 1     | -3    | 2     | Roots: 2 and 1              |
| 2\. One Real Root   | 1     | -4    | 4     | Root: 2 (Repeated)          |
| 3\. Complex Roots   | 1     | 2     | 5     | Complex Conjugate Roots     |
| 4\. \$a = 0\$ Error | 0     | 5     | 1     | Error: \$a\$ cannot be zero |

### Grade Converter Test Cases

| **Case**          | **Score** | **Expected Grade**                |
|-------------------|-----------|-----------------------------------|
| 1\. A+            | 90        | A+                                |
| 2\. A             | 75        | A                                 |
| 3\. C             | 52        | C                                 |
| 4\. D             | 44        | D                                 |
| 5\. Invalid Input | 101       | Error: Score out of range (0-100) |
