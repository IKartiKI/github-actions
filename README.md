## This is a python app

### Basics of Github Actions


---

## 🧮 Functions

- `add(a, b)` → Returns the sum of two numbers
- `sub(a, b)` → Returns the difference between two numbers

These functions are implemented in `calculator.py`.

---

## 🧪 Unit Testing

- Tests are written using Python’s built-in `unittest` framework
- Test cases validate:
  - Correct addition results
  - Correct subtraction results
  - Basic edge cases

Tests are located in the `tests/` directory.

---

## 🚀 GitHub Actions (CI)

GitHub Actions is used to:
- Automatically run unit tests
- Trigger on:
  - `push`
  - `pull_request`

The workflow:
1. Sets up Python
2. Installs dependencies
3. Runs all unit tests
4. Fails the build if any test fails

Workflow file location:
