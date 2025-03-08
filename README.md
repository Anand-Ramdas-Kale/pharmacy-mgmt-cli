# CLI Database Management System

This is a command-line database system written in C, demonstrating database creation and maintenance.

## Quick Start
```sh
$ make
$ ./check
```

## Project Structure
- **`main.c`**: Handles user interactions and CLI commands.
- **`utils.c`**: Implements core database operations.
- **`io.c`**: Handles command line interface
- **`trie.c`**: Manages trie function definitions
- **`include.h`**: contains all the structure and function declarations exept tries'

## Usage
You can modify the respective source files based on your requirements to extend functionality.

## Compilation
Ensure you have `make` installed, then compile the project using:
```sh
make
```

## Running the Program
After compilation, execute:
```sh
./check
```
This runs the CLI database system.

## Dependencies
- GCC or Clang (for compiling C code)
- Make (for building the project)

## Customization
Since essential utilities (functions) are written in separate files based on their use cases, modifying and extending the project is straightforward.
