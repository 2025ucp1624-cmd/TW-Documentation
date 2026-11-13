
# Doxygen - Automatic Code Documentation

## What I Learned

Doxygen is an open-source documentation generator used with programming languages such as C, C++, Python, and Java. It reads specially formatted comments written inside source code and converts them into documentation.

It is mainly useful for documenting functions, classes, libraries, and APIs.

## Basic Syntax

In C++, we can write documentation comments using `/** ... */` and special tags.

```cpp
/**
 * @brief Calculates the sum of two numbers.
 * @param a First number
 * @param b Second number
 * @return Sum of the two numbers
 */
int add(int a, int b) {
    return a + b;
}
```

Doxygen reads these comments and uses them to generate documentation.

## Basic Workflow

1. Write specially formatted comments in the source code.
2. Generate a configuration file using `doxygen -g Doxyfile`.
3. Run `doxygen Doxyfile`.
4. Open the generated HTML documentation, usually `html/index.html`.

## Important Concepts

 `@brief`  Gives a short description 
 `@param`  Describes a function parameter 
 `@return`  Describes the return value 
 `@author`  Specifies the author 
 `@note`  Adds an additional note 
 `Doxyfile`  Stores Doxygen configuration settings 

Doxygen can generate HTML, LaTeX/PDF, and other documentation formats. It can also create cross-references, call graphs, and inheritance diagrams.

## Practical Applications

- Documenting C++ classes and functions.
- Creating reference manuals for software libraries.
- Helping developers understand and maintain large projects.
- Generating API documentation automatically.

## My Understanding

I learned that Doxygen helps keep code documentation connected to the actual source code. Instead of writing a separate manual manually, we add meaningful comments near functions and classes, and Doxygen converts them into organized documentation. This makes software easier to understand, maintain, and use.
