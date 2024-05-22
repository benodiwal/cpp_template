# C++ Coding Guidelines

## General Guidelines
- Follow the C++ Core Guidelines: https://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines
- Use modern C++ features (C++11 and later).
- Prefer `auto` for type inference.
- Use smart pointers (`std::unique_ptr`, `std::shared_ptr`) instead of raw pointers.

## Naming Conventions
- **Classes and Structs**: PascalCase (e.g., `MyClass`)
- **Functions**: camelCase (e.g., `myFunction`)
- **Variables**: camelCase (e.g., `myVariable`)
- **Constants**: UPPER_CASE (e.g., `MY_CONSTANT`)

## Formatting
- Use 4 spaces for indentation.
- Limit lines to 80 characters.
- Place braces on the same line for functions and control structures.

## Comments
- Use `//` for single line comments.
- Use `/* */` for multi-line comments.
- Document all public functions with Doxygen comments.

## Error Handling
- Prefer exceptions over error codes.
- Use `try` and `catch` blocks to handle exceptions.

## Testing
- Write unit tests for all public functions.
- Use assertions to validate assumptions.
