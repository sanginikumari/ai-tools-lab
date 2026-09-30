# AI Tools Lab

## Project Description

AI Tools Lab is a beginner-friendly Python project for practicing basic programming concepts and working with GitHub. It includes a simple first-commit demonstration, a sorting algorithm, and a small collection of reusable utility functions.

## Features

- Print a greeting with `hello.py` as a first-commit demonstration.
- Sort a list of values in ascending order with Bubble Sort.
- Check whether a string is a palindrome.
- Count the words in a piece of text.
- Convert temperatures from Celsius to Fahrenheit.

## Installation Instructions

You need Python 3 installed. This project uses only the Python standard library, so no additional packages are required.

Clone the repository and move into the project directory:

```bash
git clone <repository-url>
cd ai-tools-lab
```

Run the greeting script with:

```bash
python hello.py
```

On some systems, use `python3` instead of `python`.

## Usage

Import the functions from their modules and call them in your own Python code:

```python
from sorting import bubble_sort
from utils import count_words, celsius_to_fahrenheit, is_palindrome

numbers = [5, 2, 9, 1]
bubble_sort(numbers)
print(numbers)  # [1, 2, 5, 9]

print(is_palindrome("radar"))  # True
print(count_words("Python is fun to learn"))  # 5
print(celsius_to_fahrenheit(0))  # 32.0
```

`bubble_sort` sorts the list in place and returns that same list. `count_words` treats runs of whitespace as separators. `is_palindrome` compares the string as written, so its check is case-sensitive and includes spaces and punctuation.

## Project Structure

```text
ai-tools-lab/
├── hello.py       # Basic GitHub and first-commit demonstration
├── sorting.py     # Bubble Sort implementation
├── utils.py       # String and temperature utility functions
└── README.md      # Project documentation
```

## Contributors

Contributions are welcome. Add contributor names or GitHub profiles here as the project grows.

## License

This project is distributed under the [MIT License](https://opensource.org/license/mit/).
