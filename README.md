
# Library Management System 

This project is a simple but robust **Library Management System** written in Python. It models books and a library using object-oriented programming and demonstrates how to:

- Validate ISBN-13 codes
- Add or remove books from a library
- Borrow and return books while tracking available copies
- Print a readable summary of library contents

##  Features

- `Book` class with:
  - Title, author, ISBN-13, and copy count
  - ISBN-13 format validation method
- `Library` class that:
  - Inherits from Python’s built-in `dict`
  - Uses ISBN-13 as keys and `Book` objects as values
  - Adds/removes books (with validation)
  - Handles borrowing and returning copies with checks
  - Prints human-readable book listings

##  Files Included

- `library_management.ipynb`: Jupyter notebook with full code and inline documentation
- `README.md`: This file

##  How to Use

1. Clone this repository
2. Open `library_management.ipynb` in JupyterLab or VS Code
3. Run all cells to simulate library operations

##  Sample Output

Library Contents:
Nonlinear Dynamics And Chaos: ... 
Global Political Economy ... 


## 🔎 ISBN Validation

The system checks each book's ISBN-13 using the official algorithm and prevents books with invalid ISBNs from being added to the library.

## 📚 Book Examples

Books include both:
- Academic titles (e.g., *Nonlinear Dynamics*, *Political Economy*)
- User-defined favorites (e.g., *Python Programming*, *AI: A Modern Approach*)

## ✅ Prerequisites

No additional libraries needed (only uses Python's built-in features and standard libraries).

## 👤 Author

Krishna Suresh  
[Your GitHub profile link here]

## 📄 License

This project is open-source under the MIT License.


