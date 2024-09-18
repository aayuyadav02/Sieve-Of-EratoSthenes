# Sieve-Of-EratoSthenes
A simple implementation of the Sieve of Eratosthenes algorithm to find all prime numbers up to a given limit in Java.


Table of Contents

- #about
- #features
- #installation
- #usage
- #example
- #contributing
- #license


About

The Sieve of Eratosthenes is an ancient algorithm for finding all prime numbers up to a given limit. This implementation provides a simple and efficient way to generate prime numbers.


Features

- Finds all prime numbers up to a given limit
- Optimized for performance
- Easy to use API


Installation

To install, simply clone this repository and compile the code.



bash
git clone (https://github.com/aayuyadav02/Sieve-Of-EratoSthenes/edit/main/README.md)
cd sieve-of-eratosthenes
make



Usage

To use the Sieve of Eratosthenes, simply call the sieve function with the desired limit.



Example

Find all prime numbers up to 100.

#include "sieve.h"

int main() {
    int limit = 100;
    int* primes = sieve(limit);
    for (int i = 0; primes[i] != -1; i++) {
        printf("%d ", primes[i]);
    }
    return 0;
}



Contributing

Contributions are welcome! Please submit pull requests against the master branch.



License

This project is licensed under the MIT License.


Copyright (c) 2024 Aayush Yadav


Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:


The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.


THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


