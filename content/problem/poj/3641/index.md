---
title: 【POJ】[3641]Pseudoprime numbers
type: post
slug: poj-3641
categories:
  - poj
ProblemParams:
    ProblemTitle: "Pseudoprime numbers"
    TimeLimit: "1000MS"
    MemoryLimit: "65536K"
---

## Description

Fermat's theorem states that for any prime number *p* and for any integer *a* > 1, *ap* = *a* (mod *p*). That is, if we raise *a* to the *p*th power and divide by *p*, the remainder is *a*. Some (but not very many) non-prime values of *p*, known as base-*a* pseudoprimes, have this property for some *a*. (And some, known as Carmichael Numbers, are base-*a* pseudoprimes for all *a*.)

Given 2 < *p* ≤ 1000000000 and 1 < *a* < *p*, determine whether or not *p* is a base-*a* pseudoprime.

## Input

Input contains several test cases followed by a line containing "0 0". Each test case consists of a line containing *p* and *a*.

## Output

Input contains several test cases followed by a line containing "0 0". Each test case consists of a line containing *p* and *a*.

## Sample Input

```
3 2
10 3
341 2
341 3
1105 2
1105 3
0 0

```

## Sample Output

```
no
no
yes
no
yes
yes

```

## Source

[Waterloo Local Contest](http://poj.org/searchproblem?field=source&key=Waterloo+Local+Contest), 2007.9.23
