---
title: 【Codeforces】[638A]Home Numbers
type: post
slug: codeforces-638A
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "Home Numbers"
    TimeLimit: "1 second"
    MemoryLimit: "256 megabytes"
---

## Description

The main street of Berland is a straight line with $n$ houses built along it ($n$ is an even number). The houses are located at both sides of the street. The houses with odd numbers are at one side of the street and are numbered from $1$ to $n - 1$ in the order from the beginning of the street to the end (in the picture: from left to right). The houses with even numbers are at the other side of the street and are numbered from $2$ to $n$ in the order from the end of the street to its beginning (in the picture: from right to left). The corresponding houses with even and odd numbers are strictly opposite each other, that is, house $1$ is opposite house $n$, house $3$ is opposite house $n - 2$, house $5$ is opposite house $n - 4$ and so on.

<div style="text-align: center;"><img class="tex-graphics" src="https://r2-oj.boiltask.com/codeforces-638A/f1f2af350938040d09a0bd5e4b474ad3" style="max-width: 100.0%;max-height: 100.0%;"></div>

Vasya needs to get to house number $a$ as quickly as possible. He starts driving from the beginning of the street and drives his car to house $a$. To get from the beginning of the street to houses number $1$ and $n$, he spends exactly $1$ second. He also spends exactly one second to drive the distance between two neighbouring houses. Vasya can park at any side of the road, so the distance between the beginning of the street at the houses that stand opposite one another should be considered the same.

Your task is: find the minimum time Vasya needs to reach house $a$.

## Input

The first line of the input contains two integers, $n$ and $a$ ($1 ≤ a ≤ n ≤ 100 000$) — the number of houses on the street and the number of the house that Vasya needs to reach, correspondingly. It is guaranteed that number $n$ is even.

## Output

Print a single integer — the minimum time Vasya needs to get from the beginning of the street to house $a$.

## Examples

### Input

```
4 2

```

### Output

```
2

```

### Input

```
8 5

```

### Output

```
3

```

## Note

In the first sample there are only four houses on the street, two houses at each side. House $2$ will be the last at Vasya's right.

The second sample corresponds to picture with $n = 8$. House $5$ is the one before last at Vasya's left.
