# Week 6: Unit Tests

## Overview
Week 6 introduced the concept of unit testing in Python. Unit tests are designed to validate that individual units of source code, such as functions or methods, work as intended. This week's tasks involved refactoring previous problem set solutions and writing unit tests to ensure their correctness.

## Task 1: Twttr
- **Description**: Reimplement the "Setting up my twttr" problem from Week 2. The goal is to shorten a given word by omitting all vowels.
- **Testing**: `pytest test_twttr.py` tests the `shorten` function to ensure it correctly removes vowels from various inputs.

## Task 2: Back to the Bank
- **Description**: Reimplement the "Home Federal Savings Bank" problem from Week 1. The program determines the value of a greeting.
- **Testing**: `pytest test_bank.py` tests the `value` function to ensure it correctly determines the value of various greetings.

## Task 3: Re-requesting a Vanity Plate
- **Description**: Reimplement the "Vanity Plates" problem from Week 2. The program checks if a given string is a valid vanity plate.
- **Testing**: `pytest test_plates.py` tests the `is_valid` function to ensure it correctly validates various vanity plate inputs.

## Task 4: Refueling
- **Description**: Reimplement the "Fuel Gauge" problem from Week 3. The program converts a fraction to a percentage and determines the fuel gauge reading.
- **Testing**: `pytest test_fuel.py` tests the `convert` and `gauge` functions to ensure they correctly convert fractions to percentages and determine the correct fuel gauge reading.

## Reflection
Week 6 emphasized the importance of testing in software development. By writing unit tests, we can confidently make changes to our code, knowing that any regressions will be caught by our tests. This week provided hands-on experience in writing tests and understanding their significance in maintaining code quality.