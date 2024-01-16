# Basic_assembler
Basic assembler inspired from Morris Mano digital design book by java.

This repository contains a basic assembler, implemented in Java, that reads and processes assembly code, converting it into binary instructions. The assembler supports around 30 different commands and includes a class to run the generated binary numbers.

## Features

- Converts assembly code into binary instructions
- Supports approximately 30 different assembly commands
- Runs the generated binary numbers

## Getting Started

These instructions will help you get a copy of the project up and running on your local machine.

### Prerequisites

- Java Development Kit (JDK) installed on your system

### Installation

1. Clone the repository to your local machine using the following command:

   ```
   git clone https://github.com/mahdiahmadii/Basic_assembler.git
   ```

2. Navigate to the project directory:

   ```
   cd basic-assembler
   ```

### Usage

1. Place your assembly code in the `input.asm` file. Ensure that each instruction is on a new line.
2. Run the assembler by executing the following command:

   ```
   javac Assembler.java
   java Assembler
   ```

   The assembler will read the instructions from `input.asm` and generate the corresponding binary instructions.

3. The binary instructions will be saved in the `output.bin` file.

4. To execute the generated binary numbers, run the following command:

   ```
   javac BinaryRunner.java
   java BinaryRunner
   ```

   The `BinaryRunner` class will read the binary instructions from `output.bin` and execute them.

## Contributing

Contributions to this project are welcome. Feel free to submit bug reports, feature requests, or pull requests. For major changes, please open an issue first to discuss any potential modifications.


## Acknowledgments

- Inspired by the book "Computer System Architecture" by M. Morris Mano.
- Thanks to the Java community for providing valuable resources and insights.
