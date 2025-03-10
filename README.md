# Prime-Number-Generator-and-Checker_202401100400153

## Introduction

This project provides a Python script to:
1. Check whether a given number is prime.
2. Generate all prime numbers up to a specified limit.

A prime number is a natural number greater than 1 that has no positive divisors other than 1 and itself. The script helps in determining if a number is prime and allows the generation of prime numbers within a given range.

---

## Features

- **Prime Number Check**: Input a number and check if it is prime or not.
- **Prime Number Generator**: Generate a list of all prime numbers up to a specified limit.

## Methodology

The program works by using two main functions:

1. **is_prime(n)**:
   - This function checks if a number `n` is prime.
   - It does so by checking divisibility up to the square root of `n`, which optimizes performance for larger numbers.

2. **generate_primes(limit)**:
   - This function generates a list of all prime numbers from 2 up to the given `limit`.
   - It uses the `is_prime` function to filter out non-prime numbers.




