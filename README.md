# Infix to Postfix Conversion

## Aim

To implement a C program for converting an infix expression into postfix notation.

## Description

Infix notation is the normal way of writing an expression, where the operator is written between operands.

Example:
`A + B`

Postfix notation places the operator after the operands.

Example:
`AB+`

The program uses a **stack** to convert an infix expression into postfix notation based on operator precedence.

## Features

* Accepts an infix expression from the user.
* Uses stack operations.
* Handles `+`, `-`, `*`, `/`, and `^`.
* Produces the corresponding postfix expression.

## Example

**Input:**

```text
A+B*C
```

**Output:**

```text
ABC*+
```

## Technologies Used

* C Programming Language
* Stack
* GCC Compiler

## How to Run

Compile the program:

```bash
gcc infix_to_postfix.c -o infix_to_postfix
```

Run the program:

```bash
./infix_to_postfix
```

## Conclusion

The program successfully converts an infix expression into its equivalent postfix expression using a stack and operator precedence.
