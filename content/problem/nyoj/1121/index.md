---
title: 【NYOJ】[1121]Triangular Sums
type: post
slug: nyoj-1121
categories:
  - nyoj
ProblemParams:
  ProblemTitle: "Triangular Sums"
  TimeLimit: "3000 MS"
  MemoryLimit: "256 MB"
---

## 题目描述

The $n^{th}$ _Triangular_ number, $T(n) = 1 + … + n$, is the sum of the first $n $ integers. It is the number of points in a triangular array with $n $ points on side. For example $T(4)$:

$XX XX X XX X X X$

Write a program to compute the weighted sum of triangular numbers:

$W(n) = SUM[k = 1…n; k * T(k + 1)]$

## 输入描述

The first line of input contains a single integer N, (1 ≤ N ≤ 1000) which is the number of datasets that follow.  
  
Each dataset consists of a single line of input containing a single integer n, (1 ≤ n ≤300), which is the number of points on a side of the triangle.

## 输出描述

For each dataset, output on a single line the dataset number (1 through N), a blank, the value of n for the dataset, a blank, and the weighted sum ,W(n), of triangular numbers for n.

## 用例

### 用例输入

```
4
3
4
5
10
```  

### 用例输出

```
1 3 45
2 4 105
3 5 210
4 10 2145
```

## 作者

张云聪

## 来源

NYOJ
