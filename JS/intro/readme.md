**What Are JS Variables**
A JS variable is like a container that stores information. We use variables to save values that our program needs to remember and use later.
Example:
let age = 20;
**How Do You Declare Variable in JS**
In JavaScript, variables are usually declared using `let` or `const`.

### Using `let`

We use `let` when the value might change later in the program.

Example:
let age = 20;
age = 21;

The value of `age` changes from `20` to `21`.

### Using `const`

We use `const` when the value should stay the same and not be changed.

Example:
const country = "Kenya";

If you try to change the value, JavaScript will show an error.

Example:
const country = "Kenya";
country = "Uganda"; // Error
``**`**Rules for Naming Variables**
When creating variable names in JavaScript, there are some rules to follow:

-   Variable names can contain letters, numbers, underscores (`_`), and dollar signs (`$`).
-   Variable names cannot start with a number.
-   Spaces are not allowed in variable names.
-   JavaScript keywords cannot be used as variable names.
-   Variable names are case-sensitive, meaning `name` and `Name` are different variables.

### Valid Variable Names

firstName
studentAge
_totalMarks

### Invalid Variable Names
1name
student age
const

**Why they are invalid:**

-   `1name` starts with a number.
-   `student age` contains a space.
-   `const` is a JavaScript keyword.
**Variable Naming Styles**
### Camel Case

Camel Case starts with a lowercase letter, and every new word starts with a capital letter.

Examples:
firstName
studentAge

**Commonly used for:** Variable names and function names in JavaScript.

### Pascal Case

Pascal Case starts with a capital letter, and every new word also starts with a capital letter.

Examples:

```
FirstName
StudentAge

****Commonly used for:**** Class names in JavaScript.

**### Snake Case**

Snake Case uses lowercase letters and separates words with underscores.

Examples:

first_name
student_age

****Commonly used for:**** Databases, file names, and some programming languages.