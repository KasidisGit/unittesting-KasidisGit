[![Build Status](https://travis-ci.com/KasidisGit/unittesting-KasidisGit.svg?branch=master)](https://travis-ci.com/KasidisGit/unittesting-KasidisGit)
[![codecov](https://codecov.io/gh/KasidisGit/unittesting-KasidisGit/branch/master/graph/badge.svg)](https://codecov.io/gh/KasidisGit/unittesting-KasidisGit)
## Unit Testing Assignment

by Kasidis Luangwutiwong.

## Test Cases for unique

Write a table describing your test cases.

| Test case              |  Expected Result    |
|------------------------|---------------------|
| empty list             |  empty list         |
| one item               |  list with 1 item   |
| one item many times    |  list with 1 item   |
| 2 items, many times, many orders | 2 item list, items in same order  |
| nested list  |  list with nested list       |
| nested list  |  list with nested list       |
| check argument  |  error if argument are not list       |
| extreme list  |  list without dupilcate     |


## Test Cases for Fraction

| Test case              |  Expected Result    |
|------------------------|---------------------|
| str or init        | the fraction        |
| add              |  sum of 2 fraction   |
| sub    |  minus of 2 fractions   |
| eq | check equal of 2 fractions  |
| gt  |  check the more fraction       |
| ng |  negative of fraction       |
| mul  |  multiple of 2 fractions    |
| div  |  divide of 2 fractions     |
| 0/0, inf/inf, -inf/-inf, inf-inf, 0*inf  |  Determinate Form     |
| inf+inf, -inf-inf, inf*inf  |  Indeterminate Form     |
