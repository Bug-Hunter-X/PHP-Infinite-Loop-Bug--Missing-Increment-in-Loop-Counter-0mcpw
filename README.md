# PHP Infinite Loop Bug

This repository demonstrates a common PHP bug: an infinite loop caused by a missing increment in a `while` loop counter.

The `bug.php` file contains the buggy code, while `bugSolution.php` provides the corrected version.

## Bug Description

The original code uses a `while` loop to iterate until a condition is met. However, the loop counter (`$i`) is never incremented, causing the loop to continue indefinitely.

## How to Reproduce

1. Clone this repository.
2. Run `bug.php` using a PHP interpreter. Observe the infinite loop.
3. Compare it to `bugSolution.php` to see the correction.

## Solution

The solution involves correctly incrementing the loop counter variable (`$i`) within the loop body.