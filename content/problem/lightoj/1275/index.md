---
title: 【LightOJ】[1275]Internet Service Providers
type: post
slug: lightoj-1275
categories:
  - lightoj
ProblemParams:
    ProblemTitle: "Internet Service Providers"
    TimeLimit: "1 seconds"
    MemoryLimit: "64 MB"
---

## Description

A group of **N** Internet Service Provider companies (ISPs) use a private communication channel that has a maximum capacity of **C** traffic units per second. Each company transfers **T** traffic units per second through the channel and gets a profit that is directly proportional to the factor **T(C - T \* N)**. The problem is to compute the smallest value of **T** that maximizes the total profit the **N** ISPs can get from using the channel. Notice that **N, C, T**, and the optimal **T** are integer numbers.

## Input

Input starts with an integer **T (≤ 20)**, denoting the number of test cases.

Each case starts with a line containing two integers **N** and **C (0 ≤ N, C ≤ 109)**.

## Output

For each case, print the case number and the minimum possible value of **T** that maximizes the total profit. The result should be an integer.

## Sample Input

```
6
1 0
0 1
4 3
2 8
3 27
25 1000000000

```

## Sample Output

```
Case 1: 0
Case 2: 0
Case 3: 0
Case 4: 2
Case 5: 4
Case 6: 20000000

```
