---
title: 【Codeforces】[621A]Wet Shark and Odd and Even
type: post
slug: codeforces-621A
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "Wet Shark and Odd and Even"
    TimeLimit: "2 seconds"
    MemoryLimit: "256 megabytes"
---

## Description

Today, Wet Shark is given $n$ integers. Using any of these integers no more than once, Wet Shark wants to get maximum possible even (divisible by $2$) sum. Please, calculate this value for Wet Shark.

Note, that if Wet Shark uses no integers from the $n$ integers, the sum is an even integer $0$.

## Input

The first line of the input contains one integer, $n$ ($1 ≤ n ≤ 100 000$). The next line contains $n$ space separated integers given to Wet Shark. Each of these integers is in range from $1$ to $10^{9}$, inclusive.

## Output

Print the maximum possible even sum that can be obtained if we use some of the given integers.

## Examples

### Input

```
3
1 2 3

```

### Output

```
6
```

### Input

```
5
999999999 999999999 999999999 999999999 999999999

```

### Output

```
3999999996
```

## Note

In the first sample, we can simply take all three integers for a total sum of $6$.

In the second sample Wet Shark should take any four out of five integers $999 999 999$.
