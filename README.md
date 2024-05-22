# Cpp Project Template

This is a template for writing good and robust C++ code. It includes a basic project structure, CMake setup, coding guidelines, unit testing, and CI configuration.

## Project Structure

- `bin/`: Executables
- `build/`: Build output
- `docs/`: Documentation
- `include/`: Header files
- `src/`: Source files
- `tests/`: Unit tests

## Getting Started

### Prerequisites

- CMake 3.22.1 or later
- A C++14 compatible compiler
- GoogleTest (included as a submodule)

### Building the Project

```sh
cmake -S . -B build
cmake --build build
