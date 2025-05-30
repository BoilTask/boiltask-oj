---
title: 【LightOJ】[1043]Triangle Partitioning
type: post
slug: lightoj-1043
categories:
  - lightoj
ProblemParams:
    ProblemTitle: "Triangle Partitioning"
    TimeLimit: "1 seconds"
    MemoryLimit: "64 MB"
---

## Description

See the picture below.

![Triangle Partitioning](https://r2-oj.boiltask.com/lightoj-1043/25a2ba566294bd4731086140a2409432) You are given **AB**, **AC** and **BC**. **DE** is parallel to **BC**. You are also given the area ratio between **ADE** and **BDEC**. You have to find the value of **AD**.

## Input

Input starts with an integer **T (≤ 25)**, denoting the number of test cases.

Each case begins with four real numbers denoting **AB, AC, BC** and the ratio of **ADE** and **BDEC** **(ADE / BDEC)**. You can safely assume that the given triangle is a valid triangle with positive area.

## Output

For each case of input you have to print the case number and **AD**. Errors less than **10\-6** will be ignored.

## Sample Input

```
4
100 100 100 2
10 12 14 1
7 8 9 10
8.134 9.098 7.123 5.10

```

## Sample Output

```
Case 1: 81.6496580
Case 2: 7.07106781
Case 3: 6.6742381247
Case 4: 7.437454786

```
