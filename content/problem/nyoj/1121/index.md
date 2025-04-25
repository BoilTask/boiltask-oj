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

The **_n_th** _Triangular_ number, **_T_(_n_) = 1 + … + _n_**, is the sum of the first **_n_** integers. It is the number of points in a triangular array with **_n_** points on side. For example **_T_(4)**:

**

X  
X X  
X X X  
X X X X  


**

Write a program to compute the weighted sum of triangular numbers:

**_W_(_n_) = `SUM[_k_ = 1…_n_; _k_ * _T_(_k_ + 1)]`**

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
