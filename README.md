# Mini Compiler Project

This is a basic Mini Compiler developed in C++ as part of a compiler design project. The compiler performs key phases of compilation including lexical analysis, parsing, semantic analysis, symbol table construction, and intermediate code generation.

## Features

- **Lexical Analysis**: Tokenizes the input source code.
- **Parsing**: Builds syntax trees using grammar rules.
- **Semantic Analysis**: Checks for type and scope errors.
- **Symbol Table**: Maintains variable/function declarations.
- **Intermediate Code Generation**: Converts source code to an intermediate representation.
- **(Optional)**: Assembly Code Generation.

## Technologies Used

- C++
- Flex (for lexical analysis)
- Bison (for parsing)

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mini-compiler.git
   cd mini-compiler
2. Run the compiler on a sample source file:
   ```bash
   gcc filename.c -o filename && ./filename goel.mini
3. run the python library for UI :
   ```bash
   python app.py

## PROJECT STRUCTURE
   ```bash
   ├── lexer.l         # Lexical analyzer
├── parser.y        # Syntax parser
├── symbol_table.h  # Symbol table logic
├── main.cpp        # Driver code
├── Makefile
└── sample.txt      # Sample input code

   
