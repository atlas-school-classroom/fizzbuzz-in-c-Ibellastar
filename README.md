# Class Assignment: FizzBuzz
## Introduction

In this exercise you will practice working with arithmetic operators and variables with the C programming language.


You will create four functions within the **calculator.c** file called:

* **int add(int a, int b)** which adds two integers.

* **int subtract(int a, int b)** which subtracts two integers.

* **int multiply(int a, int b)** which miltiplies two integers.

* **int divide(int a, int b)** which divides two integers.

You will create a program that performs basic arithmetic operations (+, -, *, /) on two integers entered by the user within the **main()** function of the **main.c** file.
Make sure your program checks for division by 0 and invalid operators. 

### Starter Files

The starter files for this exercise are located in the `src` directory. Implement your code inside the following files:

1. `calculator.c`
2. `main.c`

### Run Checks

To check your work, run the following command:

```bash
$ make checker
```

This will run the tests and output the results.

### Output

If all checks pass, you will see the following output:

```bash
✅ Test 1 - Addition
../.github/checker/test/test_1.c:12:test_1:PASS

✅ Test 2 - Subtraction
../.github/checker/test/test_2.c:12:test_2:PASS

✅ Test 3 - Multiplication
../.github/checker/test/test_3.c:12:test_3:PASS

✅ Test 4 - Division
../.github/checker/test/test_4.c:12:test_4:PASS

Ok:                 4
Expected Fail:      0
Fail:               0
Unexpected Pass:    0
Skipped:            0
Timeout:            0
```

If there are failing checks you will see summary of the failing tests:

```
❌ Test 1 - Addition
../.github/checker/tests/test_1.c:13:test_1:FAIL: Expected 7 Was 1

❌ Test 2 - Subtraction
../.github/checker/tests/test_2.c:14:test_2:FAIL: Expected 8 Was 14

❌ Test 3 - Multiplication
../.github/checker/tests/test_3.c:14:test_3:FAIL: Expected 0 Was 4

❌ Test 4 - Division
../.github/checker/tests/test_4.c:14:test_4:FAIL: Expected -5 Was 5

Summary of Failures:

1/4 Test 1 - Addition                   FAIL            0.14s   exit status 2
2/4 Test 2 - Subtraction                FAIL            0.25s   exit status 2
3/4 Test 3 - Multiplication             FAIL            0.35s   exit status 2
4/4 Test 4 - Division                   FAIL            0.46s   exit status 2

Ok:                 0
Expected Fail:      0
Fail:               4
Unexpected Pass:    0
Skipped:            0
Timeout:            0
```

In order to complete the exercise all tests must pass.
