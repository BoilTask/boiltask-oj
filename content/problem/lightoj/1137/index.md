---
title: 【LightOJ】[1137]Expanding Rods
type: post
slug: lightoj-1137
categories:
  - lightoj
ProblemParams:
    ProblemTitle: "Expanding Rods"
    TimeLimit: "1 seconds"
    MemoryLimit: "64 MB"
---

## Description

When a thin rod of length **L** is heated **n** degrees, it expands to a new length `L' = (1 + n * C) * L`, where **C** is the coefficient of heat expansion.

![Expanding Rod](https://r2-oj.boiltask.com/lightoj-1137/db1bf707a12720dcf66ae32fb353a254)

When a thin rod is mounted on two solid walls and then heated, it expands and takes the shape of a circular segment, the original rod being the chord of the segment.

Your task is to compute the distance by which the center of the rod is displaced. That means you have to calculate **h** as in the picture.

## Input

Input starts with an integer **T (≤ 20)**, denoting the number of test cases.

Each case contains three non-negative real numbers: the initial length of the rod in millimeters **L**, the temperature change in degrees **n** and the coefficient of heat expansion of the material **C**. Input data guarantee that no rod expands by more than one-half of its original length. All the numbers will be between 0 and 1000 and there can be at most 5 digits after the decimal point.

## Output

For each case, print the case number and the displacement of the center of the rod in a single line. Errors less than **10\-6** will be ignored.

## Sample Input

```
3
1000 100 0.0001
150 10 0.00006
10 0 0.001

```

## Sample Output

```
Case 1: 61.3289915
Case 2: 2.2502024857
Case 3: 0

```
