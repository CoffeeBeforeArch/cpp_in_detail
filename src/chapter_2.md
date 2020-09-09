# Chapter 2 - Fundamental Concepts

In this chapter, we'll be looking at some of the core concepts of programming in C++. This includes:

- Data types
- Functions
- Compilation and Execution
- Comments
- Variables and Operators
- Using the standard library (for printing)

## Data Types

Every value in C++ has a type. Types determine how values are represented in memory, and how they can be used in our programs. Types in C++ come in two flavors:

- Fundamental Types
- Compound Types

### Fundamental Types

Fundamental types are those defined in the language language standard and built into the compiler. We can use them in our programs without having to include any external files or libraries. The main fundamental types are:

- `void`
- `bool`
- Character types
- Integer types
- Floating point types

#### The void Type

`void` represents an empty set of values, meaning that no value can be of type `void`. In practice, `void` is used to specify that data will not be passed to, or from some location.

#### The boolean Type

The boolean type, `bool` is used to represent the values `true` or `false`. Booleans are typically used in the results of comparisons (less than, greater, than, equal to, etc.) or the results of logical operators (AND, OR, NOT).

#### Character Types

Character types are either signed or unsigned, and are typically used to encode text. The core of the character type is the `char`. This is guaranteed to be a single byte.

The signed-ness of the character type can be changed using the keywords `signed` and `unsigned`.

#### Integer Types

Integer types are either signed or unsigned, and can be used to represent whole numbers. The core of the integer type is the `int`.

The signed-ness of the integer type can be changed using the keywords `signed` and `unsigned`. The size can be modified with the keywords `short` and `long`.

#### Floating Point Types

Floating point types are used to represent signed and unsigned decimal numbers according to the IEEE-754 Floating Point Standard. There are two key floating point types:

- Single-precision (`float`)
- Double-precision (`double`)

Single-precision floating point numbers are guaranteed to be 32 bits, and dobule-precision number are guaranteed to be 64 bits.

## Functions

A function is a block of code in C++ that we can pass value to, return values from. All functions follow the following basic structure:

```cpp
ReturnType Name(List, of, Parameters) {
  Function Body
}
```

`ReturnType` is the data type we want to return from the function. This type can also be `void`, meaning the function does not return anything.

`Name` is a user-defined name we can use to indentify and call (execute) the function.

After `Name` there is an *optional* comma-separated list of parameters (with data types) in parentheses. This specifies what types, and how many values we can pass into a function.

Our function body is wrapped in curly brackets (`{  }`) after the optional list of parameters. This is where the code we want to execute when the function is called is defined. For functions without a `void` return type, the function body is also where need to place a `return` statement. A `return` statement exits the function, and returns a value to wherever the function was called from.

Let's take a look at an example function named `my_function` that does not take any input parameters, and always returns the value `42`.

```cpp
int my_function() {
  return 42;
}
```

### The main Function

## Compilation and Execution

## Comments

## Variables and Operators

## Using the Standard Library (Printing)
