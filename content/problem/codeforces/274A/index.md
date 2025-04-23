---
title: 【Codeforces】[274A]k-Multiple Free Set
type: post
slug: codeforces-274A
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "k-Multiple Free Set"
    TimeLimit: "2 seconds"
    MemoryLimit: "256 megabytes"
---

## Description

A $_k_$\-multiple free set is a set of integers where there is no pair of integers where one is equal to another integer multiplied by $_k_$. That is, there are no two integers $_x_$ and $_y_$ $(_x_ < _y_)$ from the set, such that $_y_ = _x_·_k_$.

You're given a set of $_n_$ distinct positive integers. Your task is to find the size of it's largest $_k_$\-multiple free subset.

## Input

The first line of the input contains two integers $_n_$ and $_k_$ ($1 ≤ _n_ ≤ 10^{5}, 1 ≤ _k_ ≤ 109$). The next line contains a list of $_n_$ distinct positive integers $_a__{1}, _a_2, ..., _a__n_$ $(1 ≤ _a___{i}_ ≤ 10^{9})$.

All the numbers in the lines are separated by single spaces.

## Output

On the only line of the output print the size of the largest $_k_$\-multiple free subset of ${_a__{1}, _a_2, ..., _a__n_}$.

## Examples

### Input

```
6 2
2 3 6 5 4 10

```

### Output

```
3

```

## Note

In the sample input one of the possible maximum 2-multiple free subsets is {4, 5, 6}.
