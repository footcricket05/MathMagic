# MathMagic: Your Command Line Calculator in C++ ✨

![Calculator](https://user-images.githubusercontent.com/93007427/202865835-bb67b9d0-19d6-4a1a-b6d9-5965a9ce5992.png)

## Overview
Welcome to MathMagic, a powerful command-line calculator program written in C++. With MathMagic, users can perform basic mathematical operations as well as delve into scientific calculations. The program offers two modes of operation: regular and scientific, providing versatility to meet your mathematical needs.

## Features 🚀
- **Dual Modes**: Switch between regular and scientific modes to perform simple calculations or complex scientific functions.
- **User-Friendly**: Input a range of user-friendly commands that correspond to different operations.
- **Memory Storage**: Store and recall important numbers using the `mem` keyword.
- **Result History**: Easily access the result of a previous calculation using the `result` keyword.

## Classes 👨‍🏫
1. `Calculator`: The base class that handles basic mathematical operations, such as addition, subtraction, multiplication, and division. It's equipped with functions to display messages, prompt for user input, and perform calculations.

2. `Scientific`: A derived class that inherits from `Calculator` and extends its capabilities to perform scientific calculations, including sine, cosine, tangent, logarithm, absolute value, and exponentiation. It overrides the `welcome()` and `parseOperation()` functions to introduce its own set of operations.

## Usage 🧮
1. Choose the operation you wish to perform when prompted.
2. Provide the necessary input as requested by the selected operation.
3. Watch as MathMagic performs the calculation and displays the result.
4. You can switch between regular and scientific modes by typing `sci`.

## Nifty Features 💡
1. Use intuitive keywords like `+`, `add`, `addition`, or `sum` to trigger addition.
2. The program includes a handy memory feature to store numbers for later use.
3. The `result` keyword acts as a variable, allowing you to use the result of a previous calculation in new equations.
4. Utilize the `mem` keyword to keep track of essential results for your calculations.

## Contributing 🤝
Contributions are welcome! If you have suggestions or feedback, please don't hesitate to submit a pull request or open an issue.

## License 📜
This project is licensed under the MIT License, granting you the freedom to use, modify, and distribute the code as you see fit.

Let MathMagic simplify your calculations and unleash your mathematical wizardry! 🌟
