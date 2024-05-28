# Pascal Triangle Project

This project focuses on generating Pascal's Triangle using Python. Pascal's Triangle is a triangular array of binomial coefficients that arises in probability theory, combinatorics, and algebra.

## Table of Contents

- [Description](#description)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Description

Pascal's Triangle is a mathematical concept that results in a triangular array where each entry is the sum of the two directly above it. This project implements a function to generate the triangle up to a given number of rows.

## Prerequisites

Before you begin, ensure you have Python installed on your machine. You can download Python from the [official website](https://www.python.org/downloads/).

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/gidambayiantony/alx-interview.git

   ## Installation

To set up the project locally, follow these steps:

2. Navigate to the project directory:
   ```sh
   cd alx-interview/0x00-pascal_triangle

   ## Usage

To generate Pascal's Triangle, run the `pascal_triangle.py` script with the desired number of rows.

1. Open a terminal.
2. Run the script:
   ```sh
   python3 pascal_triangle.py


Example
Here is an example of how to use the function


from pascal_triangle import pascal_triangle

# Generate Pascal's Triangle with 5 rows
rows = 5
triangle = pascal_triangle(rows)

for row in triangle:
    print(row)



Output

[1]
[1, 1]
[1, 2, 1]
[1, 3, 3, 1]
[1, 4, 6, 4, 1]


