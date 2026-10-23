<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cplusplus/cplusplus-original.svg" alt="C++ logo" width="96" />

  # C++ Programming Foundations

  Practical console programs for building confidence with modern C++ fundamentals.

  <a href="https://isocpp.org/"><img src="https://img.shields.io/badge/C%2B%2B-17-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++17" /></a>
  <a href="https://github.com/PVegananda/cpp-programming-foundations"><img src="https://img.shields.io/badge/Platform-Cross--platform-2ea44f?style=flat-square" alt="Cross-platform" /></a>
  <a href="https://github.com/PVegananda/cpp-programming-foundations"><img src="https://img.shields.io/badge/Build-Command%20line-6f42c1?style=flat-square" alt="Command line build" /></a>
</div>

## About

This repository is a compact collection of standalone C++ console applications. Each
program focuses on a practical programming concept, from arithmetic and mathematical
formulas to conditional logic and price calculations.

The examples are intentionally small and easy to explore. They are useful as a
reference for anyone learning C++ or looking for clear starting points for their own
experiments.

## Project structure

```text
.
├── fundamentals/
│   ├── arithmetic-operations.cpp
│   ├── basic-calculations.cpp
│   └── mathematical-formulas.cpp
└── control-flow/
    ├── bulk-purchase-discount.cpp
    ├── parking-fee-calculator.cpp
    └── product-discount-calculator.cpp
```

### Included concepts

- Arithmetic operations and numeric input
- Mathematical formulas and unit conversion
- Conditional statements and nested decision-making
- Discount and pricing calculations
- Console input and formatted output

## Getting started

### Requirements

- A C++17-compatible compiler
- A terminal or command prompt

The examples can be compiled with GCC or Clang on macOS, Linux, and Windows.

### Clone the repository

```bash
git clone https://github.com/PVegananda/cpp-programming-foundations.git
cd cpp-programming-foundations
```

### Compile and run an example

```bash
mkdir -p build
g++ -std=c++17 fundamentals/arithmetic-operations.cpp \
    -o build/arithmetic-operations
./build/arithmetic-operations
```

On macOS, `clang++` can be used with the same options:

```bash
clang++ -std=c++17 control-flow/parking-fee-calculator.cpp \
    -o build/parking-fee-calculator
./build/parking-fee-calculator
```

For Windows with MinGW, add `.exe` to the output name and run the resulting
executable from Command Prompt or PowerShell.

## Download and use

All source files are available to download and use. You are welcome to study,
adapt, and build on the examples for your own projects.

## License

No license has been specified yet. If you plan to reuse these examples in another
project, please contact the repository owner first.

## Connect

If you find these examples useful, feel free to explore the repository and connect
with [PVegananda](https://github.com/PVegananda) for more C++ projects.
