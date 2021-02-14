# Google Foobar (re-ID)

This is my take on Google Foobar Level 1 (re-ID) Challenge.
<br>I use memoization concept to make the runtime faster.

## Challenge Specification:

Assign IDs by writing a function solution(n) which takes in the starting index n of string of all primes, and returns the next five digits in the string. The value of n will always be between 0 and 10000.

Input/output operations are not allowed.

The solution code must be under 32000 characters in length including new lines and and other non-printing characters.

## Test Cases:
Your code should pass the following test cases.
<br>Note that there might be hidden test cases.

Input:
<br>>solution(0)
<br>Output:
<br>>23571

Input:
<br>>solution(3)
<br>Output:
<br>>71113

## Sandbox Additional Information
Your code will run inside a Python 2.7.13 sandbox. All tests will be run by calling the solution() function.

Standard libraries are supported except for bz2, crypt, fcntl, mmap, pwd, pyexpat, select, signal, termios, thread, time, unicodedata, zipimport, zlib.
