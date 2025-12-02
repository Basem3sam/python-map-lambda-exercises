# Python Map and Lambda Exercises

A collection of Python exercises demonstrating the use of `map()` and `lambda` functions for data transformation and manipulation.

## 📚 Exercises Overview

### Exercise 1: Transform and Clean Data

Clean product names by removing extra spaces and converting to title case.

- **Input:** `[" LAPTOP ", "phone ", " Tablet", "CAMERA "]`
- **Output:** `['Laptop', 'Phone', 'Tablet', 'Camera']`

### Exercise 2: Convert Temperatures

Convert temperatures from Celsius to Fahrenheit using the formula F = (9/5) × C + 32.

- **Input:** `[0, 10, 20, 30, 40]`
- **Output:** `[32.0, 50.0, 68.0, 86.0, 104.0]`

### Exercise 3: Multiple Transformations

Apply multiple operations (square and add 10) in a single transformation.

- **Input:** `[1, 2, 3, 4, 5]`
- **Output:** `[11, 14, 19, 26, 35]`

### Exercise 4: Extract First and Last Characters

Create tuples of first and last characters from words.

- **Input:** `["python", "lambda", "programming", "map", "function"]`
- **Output:** `[('p', 'n'), ('l', 'a'), ('p', 'g'), ('m', 'p'), ('f', 'n')]`

### Exercise 5: Nested Map Transformation (Challenge 🌟)

Use nested maps to increase student marks by 5% and round the results.

- **Input:** `[[45, 80, 70], [90, 60, 100], [88, 76, 92]]`
- **Output:** `[[47, 84, 74], [95, 63, 105], [92, 80, 97]]`

### Exercise 6: Normalize Numbers

Normalize a list of numbers between 0 and 1 using min-max normalization.

- **Input:** `[10, 20, 30, 40, 50]`
- **Output:** `[0.0, 0.25, 0.5, 0.75, 1.0]`

### Exercise 7: Extract Word Lengths

Get the length of each word in multiple sentences using nested maps.

- **Input:** Various sentences
- **Output:** List of word length lists

## 🚀 Getting Started

### Prerequisites

- Python 3.x

### Running the Exercises

Clone the repository:

```bash
git clone https://github.com/basem3sam/python-map-lambda-exercises.git
cd python-map-lambda-exercises
```

Run any exercise:

```bash
python exercise_1.py
python exercise_2.py
python exercise_3.py
python exercise_4.py
python exercise_5.py
python exercise_6.py
python exercise_7.py
```

Or run all exercises at once:

```bash
python run_all.py
```

## 📖 Key Concepts

### `map()` Function

The `map()` function applies a given function to each item of an iterable and returns a map object (iterator).

**Syntax:**

```python
map(function, iterable)
```

### `lambda` Functions

Lambda functions are small anonymous functions defined with the `lambda` keyword.

**Syntax:**

```python
lambda arguments: expression
```

### Combining `map()` and `lambda`

```python
# Example: Square all numbers
numbers = [1, 2, 3, 4, 5]
squared = list(map(lambda x: x**2, numbers))
# Result: [1, 4, 9, 16, 25]
```

## 📁 Project Structure

```
python-map-lambda-exercises/
│
├── README.md
├── exercise_1.py          # Transform and Clean Data
├── exercise_2.py          # Convert Temperatures
├── exercise_3.py          # Multiple Transformations
├── exercise_4.py          # Extract First and Last Characters
├── exercise_5.py          # Nested Map Transformation
├── exercise_6.py          # Normalize Numbers
├── exercise_7.py          # Extract Word Lengths
└── run_all.py            # Run all exercises
```

## 🤝 Contributing

Feel free to fork this repository and submit pull requests. You can also open issues for suggestions or bugs.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

Your Name

- GitHub: [@basem3sam](https://github.com/basem3sam)

## ⭐ Show Your Support

Give a ⭐️ if this project helped you learn about `map()` and `lambda` in Python!
