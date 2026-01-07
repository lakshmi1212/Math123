# Math Operations

This project provides basic math operations such as addition and subtraction. It is designed to integrate seamlessly into CI/CD workflows.

## Files

- `src/math_operations.py`: Contains the implementation of addition and subtraction functions.
- `tests/test_add.py`: Tests for the addition function.
- `tests/test_subtract.py`: Tests for the subtraction function.
- `math.json`: Metadata for CI/CD pipeline.
- `requirements.txt`: Dependencies for the project.

## Usage

1. Clone the repository.
2. Install dependencies from `requirements.txt`.
3. Run tests using `pytest`.

## CI/CD Workflow

The CI/CD pipeline is triggered on push and pull request events to the `main` branch. It runs Python tests using `pytest`.