
# Python-like Interpreter in C++

This project is a custom interpreter built in C++ that simulates Python-like behavior for arithmetic, logical, and assignment operations. It includes support for control structures such as if statements, for loops, and block execution.

## Technologies Used
* C++ 
* CMake 

## Project Structure
* code/: Contains the source files (.cpp).
* build/: Contains CMakeLists.txt - configuration for the CMake build system.
* examples/: Contains .txt files with sample Python-like code to be interpreted.

### How to Run the Project
To run this project, you need to have a C++ compiler (like GCC or MSVC) and CMake installed.
Navigate to the project folder and run the following commands:
```bash
# Navigate to the build directory
cd build

# Generate the build files
cmake .

# Build the executable
cmake --build .
```

After building the project, follow these steps to run a Python-like script:

* From the build/ directory, run:

```bash
./exe
```
* Enter the file path:  
The program will prompt you with enter file path:. Type the relative path to your script (e.g., from your examples/ folder):
```bash
../examples/pythonCode1.txt
```
* View Output:  
The interpreter will process the file and display the output of assignments and print statements directly in the command line.
