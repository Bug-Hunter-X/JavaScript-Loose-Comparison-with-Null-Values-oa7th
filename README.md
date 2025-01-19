# JavaScript Loose Comparison with Null Values

This repository demonstrates a common JavaScript error related to loose comparison (==) with null values.  Loose comparison can lead to unexpected results, particularly when dealing with null or undefined.

## The Bug
The `foo` function in `bug.js` uses loose comparison.  While it intends to handle null values, it doesn't address the difference between `null` and `NaN` (Not a Number).

## The Solution
The `bugSolution.js` file provides a corrected version of the function, using strict equality (===) to explicitly check for `null` and correctly handles the `NaN` case.

## How to Run
1. Clone the repository.
2. Open `bug.js` and `bugSolution.js` in your preferred JavaScript environment.
3. Run each file to observe the difference in output.
