---
title: 【LightOJ】[1214]Large Division
type: post
slug: lightoj-1214
categories:
  - lightoj
ProblemParams:
    ProblemTitle: "Large Division"
    TimeLimit: "1 seconds"
    MemoryLimit: "64 MB"
---

## Description

Given two integers, **a** and **b**, you should check whether **a** is divisible by **b** or not. We know that an integer **a** is divisible by an integer **b** if and only if there exists an integer **c** such that **a = b \* c**.

## Input

Input starts with an integer **T (≤ 525)**, denoting the number of test cases.

Each case starts with a line containing two integers **a (-10200 ≤ a ≤ 10200)** and **b (|b| > 0, b fits into a 32 bit signed integer)**. Numbers will not contain any leading zeroes.

## Output

For each case, print the case number first. Then print `divisible` if **a** is divisible by **b**. Otherwise print `not divisible`.

## Sample Input

```
6
101 101
0 67
-101 101
7678123668327637674887634 101
11010000000000000000 256
-202202202202000202202202 -101

```

## Sample Output

```
Case 1: divisible
Case 2: divisible
Case 3: divisible
Case 4: not divisible
Case 5: divisible
Case 6: divisible

```
