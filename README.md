# Command Line Calculator Using C++
 
![image](https://user-images.githubusercontent.com/93007427/202865835-bb67b9d0-19d6-4a1a-b6d9-5965a9ce5992.png)


## Overview
This is a command-line calculator program written in C++ that allows users to perform basic mathematical operations as well as scientific calculations. The program has two modes, regular and scientific, that the user can switch between.


## Features
1. Two modes of operation: regular and scientific.

2. Users can enter a range of inputs that correspond to each operation.

3. A memory feature allows the user to store a number for later use and access it using the keyword `mem`.

4. The result of a previous calculation is always stored and can be accessed using the keyword `result`.


## Classes
1. `Calculator`: The base class that performs basic mathematical operations such as addition, subtraction, multiplication, and division. It has data members and member functions that display messages to the screen, prompt for user input, and perform calculations.

2. `Scientific`: A derived class that inherits from the `Calculator` class and performs scientific calculations such as sine, cosine, tangent, logarithm, absolute value, and power. It overrides the `welcome()` and `parseOperation()` functions to add its own options and calculations.


## Usage
The program flow is as follows:

1. The user is prompted for the desired operation.

2. Additional data is requested from the user based on the selected operation.

3. The calculation is performed, and the result is displayed.

4. The program repeats from step 1.

The program polymorphically calls the appropriate member functions depending on the current mode (scientific vs simple). Users can switch between the two modes by entering the keyword `sci`.


## Nifty Features
1. Users can enter keywords such as `+`, `add`, `addition`, or `sum` to trigger the addition operation.

2. The program has a memory feature that allows users to store a number in memory and access it later for further computation.

3. The `result` keyword can be used as a number, allowing users to perform calculations using the result of a previous operation.

4. The `mem` keyword allows users to store an important result for later use in their calculations.


## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or feedback.


## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as you see fit.
