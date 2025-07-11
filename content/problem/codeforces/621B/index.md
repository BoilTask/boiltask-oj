---
title: 【Codeforces】[621B]Wet Shark and Bishops
type: post
slug: codeforces-621B
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "Wet Shark and Bishops"
    TimeLimit: "2 seconds"
    MemoryLimit: "256 megabytes"
---

## Description

Today, Wet Shark is given $n$ bishops on a $1000$ by $1000$ grid. Both rows and columns of the grid are numbered from $1$ to $1000$. Rows are numbered from top to bottom, while columns are numbered from left to right.

Wet Shark thinks that two bishops attack each other if they share the same diagonal. Note, that this is the only criteria, so two bishops may attack each other (according to Wet Shark) even if there is another bishop located between them. Now Wet Shark wants to count the number of pairs of bishops that attack each other.

## Input

The first line of the input contains $n$ ($1 ≤ n ≤ 200 000$) — the number of bishops.

Each of next $n$ lines contains two space separated integers $x_{i}$ and $y_{i}$ ($1 ≤ x_{_{i}}, yi ≤ 1000$) — the number of row and the number of column where $i$\-th bishop is positioned. It's guaranteed that no two bishops share the same position.

## Output

Output one integer — the number of pairs of bishops which attack each other.

## Examples

### Input

```
5
1 1
1 5
3 3
5 1
5 5

```

### Output

```
6

```

### Input

```
3
1 1
2 3
3 5

```

### Output

```
0

```

## Note

In the first sample following pairs of bishops attack each other: $(1, 3)$, $(1, 5)$, $(2, 3)$, $(2, 4)$, $(3, 4)$ and $(3, 5)$. Pairs $(1, 2)$, $(1, 4)$, $(2, 5)$ and $(4, 5)$ do not attack each other because they do not share the same diagonal.
