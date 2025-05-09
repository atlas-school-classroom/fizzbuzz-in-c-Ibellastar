# Class Assignment: FizzBuzz
## Introduction

In this exercise you will create a function called **void fizz_buzz(int number)** that takes in integers and prints Fizz, Buzz, or Fizzbuzz based on the number inputed.

For multiples of 3, print "Fizz" instead of the number. For multiples of 5, print "Buzz". For numbers which are multiples of both 3 and 5, print "FizzBuzz".

### Starter Files

The starter files for this exercise are located in the `src` directory. Implement your code inside the **void fizz_buzz(int number)** function in ths following file:

1. `fizz_buzz.c`

### Run Checks

To check your work, run the following command:

```bash
$ make checker
```

This will run the tests and output the results.

### Output

If all checks pass, you will see the following output:

```bash
✅ Test 1 - Prints 1 through 3
Expected output:
1
2
Fizz

Actual output:
1
2
Fizz

../.github/checker/tests/test_1/test_1.c:13:test_1:PASS

✅ Test 2 - Prints 1 through 5
Expected output:
1
2
Fizz
4
Buzz

Actual output:
1
2
Fizz
4
Buzz

../.github/checker/tests/test_2/test_2.c:13:test_2:PASS

✅ Test 3 - Prints 1 through 15
Expected output:
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz

Actual output:
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz

../.github/checker/tests/test_3/test_3.c:13:test_3:PASS

✅ Test 4 - Prints 1 through 17
Expected output:
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
17

Actual output:
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
17

../.github/checker/tests/test_4/test_4.c:13:test_4:PASS

Ok:                 4
Expected Fail:      0
Fail:               0
Unexpected Pass:    0
Skipped:            0
Timeout:            0
```

If there are failing checks you will see summary of the failing tests:

```
❌ Test 1 - Prints 1 through 3
Expected output:
1
2
Fizz

Actual output:
1
2
3

../.github/checker/tests/test_1/test_1.c:36:test_1:FAIL: Expected '1\n2\nFizz\n' Was '1\n2\n3\n'

❌ Test 2 - Prints 1 through 5
Expected output:
1
2
Fizz
4
Buzz

Actual output:
1
2
3
4
5

../.github/checker/tests/test_2/test_2.c:36:test_2:FAIL: Expected '1\n2\nFizz\n4\nBuzz\n' Was '1\n2\n3\n4\n5\n'

❌ Test 3 - Prints 1 through 15
Expected output:
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz

Actual output:
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15


../.github/checker/tests/test_3/test_3.c:36:test_3:FAIL: Expected '1\n2\nFizz\n4\nBuzz\nFizz\n7\n8\nFizz\nBuzz\n11\nFizz\n13\n14\nFizzBuzz\n' Was '1\n2\n3\n4\n5\n6\n7\n8\n9\n10\n11\n12\n13\n14\n15\n'

❌ Test 4 - Prints 1 through 17
Expected output:
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
17

Actual output:
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17

../.github/checker/tests/test_4/test_4.c:36:test_4:FAIL: Expected '1\n2\nFizz\n4\nBuzz\nFizz\n7\n8\nFizz\nBuzz\n11\nFizz\n13\n14\nFizzBuzz\n16\n17\n' Was '1\n2\n3\n4\n5\n6\n7\n8\n9\n10\n11\n12\n13\n14\n15\n16\n17\n'

Summary of Failures:

1/4 Test 1 - Prints 1 through 3              FAIL            0.14s   exit status 2
2/4 Test 2 - Prints 1 through 5              FAIL            0.25s   exit status 2
3/4 Test 3 - Prints 1 through 15             FAIL            0.35s   exit status 2
4/4 Test 4 - Prints 1 through 17             FAIL            0.46s   exit status 2

Ok:                 0
Expected Fail:      0
Fail:               4
Unexpected Pass:    0
Skipped:            0
Timeout:            0
```

In order to complete the exercise all tests must pass.
