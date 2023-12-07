## Prerequisites
Before you start, make sure you have the following installed on your system:

- [Cygwin](https://www.cygwin.com/): A large collection of GNU and Open Source tools, which provides functionalities similar to a Linux distribution on Windows.
- [GCC Compiler](https://gcc.gnu.org/): The GNU Compiler Collection for compiling C code.
- [Visual Studio Code](https://code.visualstudio.com/): Code editor.

# Lox_bytecode
Implementation of the Lox programming language Bytecode Virtual Machine from the textbook(Part III): [*Crafting Interpreters* by Robert Nystrom](https://craftinginterpreters.com/) in C.

# Chapter Progress
- The "Lox_Bytecode_Progress" folder contains the code for each chapter completed in the textbook. 
# Install/Build
- Navigate to the project folder: `cd Lox_Bytecode/Interpreter_Lox`
- Build the Project using the provided makefile:
```
make clean
make
```
- This will create a "obj" folder and also a "bin" folder that contains the compiled executable file "my_program"
# Usage 
- Complete Install/Build.
- Run the interpreter by entering this into the terminal: `./bin/my_program`
- After this, a REPL will showup where you can code in Lox!
# Testing
- Tests are in the "Interpreter_Lox/test" folder.
- To run the tests type:
```
./bin/my_program --test test > output1.txt 2>&1
```
- This command runs the executable and redirects stderr to the same location as stdout.
- The following part of the main code in runTestRepo ensures that the output will be flushed to the file immediately after each print statement: `fflush(stdout);  // Flush stdout`
- The output of the tests on my machine is in the "TestOutput.txt" file : [Test Output](TestOutput.txt)
# Repository Layout
*   `Lox_Bytecode_Progress/` - The code of the Interpreter developed chapter by chapter
*   `Interpreter_Lox/` - The Interpreter project folder with all necessary files.
*   `Interpreter_Lox/test/` - All test files.
*   `TestOutput.txt` – Output of the tests.
# ChatGPT
- For this assignment's preparation, the author(s) have utilized ChatGPT, a language model created by OpenAI. 
Within this assignment, the ChatGPT was used for purposes such as brainstorming, grammatical correction, writing paraphrasing, and learning.
