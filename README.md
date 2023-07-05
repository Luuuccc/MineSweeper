# Minesweeper

## Description
Minesweeper is a classic game where the player uncovers cells on a grid, trying to avoid mines. This project provides a function that takes a grid as input, where each hash (#) represents a mine and each dash (-) represents a mine-free spot. The function returns a modified grid where each dash is replaced by a digit indicating the number of mines adjacent to that spot, both horizontally, vertically, and diagonally. The goal of the game is to uncover all the mine-free spots without triggering any mines.

This project is important as it allows players to enjoy the popular Minesweeper game in a simplified form. It provides a convenient way to generate the grid with mine counts, allowing players to focus on playing the game rather than manual calculations.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)

## Installation
To install and run the Minesweeper project locally, follow these steps:

1. Clone the repository to your local machine using the following command:
>git clone https://github.com/Luuuccc/finalCapstone.git
2. Navigate to the project directory:
>cd minesweeper
3. Ensure you have Python installed on your machine (version 3.0 or above).
4. Install any dependencies required by the project using the following command:
>pip install -r requirements.txt
5. You are now ready to use the Minesweeper function!

## Usage

   To use the Minesweeper function, follow these instructions:

1. Open the Python interpreter or create a Python script in your preferred editor.
2. Import the Minesweeper module:
```python
from minesweeper import minesweeper

Example of an input:
[ ["-", "-", "-", "#", "#"],
["-", "#", "-", "-", "-"],
["-", "-", "#", "-", "-"],
["-", "#", "#", "-", "-"],
["-", "-", "-", "-", "-"] ]

Example of the expected output:
[ ["1", "1", "2", "#", "#"],
["1", "#", "3", "3", "2"],
["2", "4", "#", "2", "0"],
["1", "#", "#", "2", "0"],
["1", "2", "2", "1", "0"] ]

```

## Credits
This Minesweeper project was created by Lucy Chen during HyperionDev Bootcamp. I would like to thank HyperionDev and the open-source community for their contributions and support.
