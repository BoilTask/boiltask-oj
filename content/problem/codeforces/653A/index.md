---
title: 【Codeforces】[653A]Bear and Three Balls
type: post
slug: codeforces-653A
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "Bear and Three Balls"
    TimeLimit: "2 seconds"
    MemoryLimit: "256 megabytes"
---

## Description

Limak is a little polar bear. He has $n$ balls, the $i$\-th ball has size $t_{i}$.

Limak wants to give one ball to each of his three friends. Giving gifts isn't easy — there are two rules Limak must obey to make friends happy:

*   No two friends can get balls of the same size.
*   No two friends can get balls of sizes that differ by more than $2$.

For example, Limak can choose balls with sizes $4$, $5$ and $3$, or balls with sizes $90$, $91$ and $92$. But he can't choose balls with sizes $5$, $5$ and $6$ (two friends would get balls of the same size), and he can't choose balls with sizes $30$, $31$ and $33$ (because sizes $30$ and $33$ differ by more than $2$).

Your task is to check whether Limak can choose three balls that satisfy conditions above.

## Input

The first line of the input contains one integer $n$ ($3 ≤ n ≤ 50$) — the number of balls Limak has.

The second line contains $n$ integers $t_{1}, t_{2}, ..., t_{n}$ ($1 ≤ t_{i} ≤ 1000$) where $t_{i}$ denotes the size of the $i$\-th ball.

## Output

Print "YES" (without quotes) if Limak can choose three balls of distinct sizes, such that any two of them differ by no more than $2$. Otherwise, print "NO" (without quotes).

## Examples

### Input

```
4
18 55 16 17

```

### Output

```
YES

```

### Input

```
6
40 41 43 44 44 44

```

### Output

```
NO

```

### Input

```
8
5 972 3 4 1 4 970 971

```

### Output

```
YES

```

## Note

In the first sample, there are $4$ balls and Limak is able to choose three of them to satisfy the rules. He must must choose balls with sizes $18$, $16$ and $17$.

In the second sample, there is no way to give gifts to three friends without breaking the rules.

In the third sample, there is even more than one way to choose balls:

1.  Choose balls with sizes $3$, $4$ and $5$.
2.  Choose balls with sizes $972$, $970$, $971$.
