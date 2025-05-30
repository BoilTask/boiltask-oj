---
title: 【POJ】[1543]Perfect Cubes
type: post
slug: poj-1543
categories:
  - poj
ProblemParams:
    ProblemTitle: "Perfect Cubes"
    TimeLimit: "1000MS"
    MemoryLimit: "10000K"
---

## Description

For hundreds of years Fermat's Last Theorem, which stated simply that for n > 2 there exist no integers a, b, c > 1 such that a^n = b^n + c^n, has remained elusively unproven. (A recent proof is believed to be correct, though it is still undergoing scrutiny.) It is possible, however, to find integers greater than 1 that satisfy the "perfect cube" equation a^3 = b^3 + c^3 + d^3 (e.g. a quick calculation will show that the equation 12^3 = 6^3 + 8^3 + 10^3 is indeed true). This problem requires that you write a program to find all sets of numbers {a,b,c,d} which satisfy this equation for a <= N.

## Input

One integer N (N <= 100).

## Output

One integer N (N <= 100).

## Sample Input

```
24
```

## Sample Output

```
Cube = 6, Triple = (3,4,5)
Cube = 12, Triple = (6,8,10)
Cube = 18, Triple = (2,12,16)
Cube = 18, Triple = (9,12,15)
Cube = 19, Triple = (3,10,18)
Cube = 20, Triple = (7,14,17)
Cube = 24, Triple = (12,16,20)
```

## Source

[Mid-Central USA 1995](http://poj.org/searchproblem?field=source&key=Mid-Central+USA+1995)
