---
title: 【Codeforces】[300A]Array
type: post
slug: codeforces-300A
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "Array"
    TimeLimit: "2 seconds"
    MemoryLimit: "256 megabytes"
---

## Description

Vitaly has an array of $n$ distinct integers. Vitaly wants to divide this array into three non-empty sets so as the following conditions hold:

1.  The product of all numbers in the first set is less than zero $( < 0)$.
2.  The product of all numbers in the second set is greater than zero $( > 0)$.
3.  The product of all numbers in the third set is equal to zero.
4.  Each number from the initial array must occur in exactly one set.

Help Vitaly. Divide the given array.

## Input

The first line of the input contains integer $n$ $(3 ≤ n ≤ 100)$. The second line contains $n$ space-separated distinct integers $a_{1}, a_{2}, ..., a_{n}$ $(|a_{i}| ≤ 10^{3})$ — the array elements.

## Output

In the first line print integer $n_{1}$ $(n_{1} > 0)$ — the number of elements in the first set. Then print $n_{1}$ numbers — the elements that got to the first set.

In the next line print integer $n_{2}$ $(n_{2} > 0)$ — the number of elements in the second set. Then print $n_{2}$ numbers — the elements that got to the second set.

In the next line print integer $n_{3}$ $(n_{3} > 0)$ — the number of elements in the third set. Then print $n_{3}$ numbers — the elements that got to the third set.

The printed sets must meet the described conditions. It is guaranteed that the solution exists. If there are several solutions, you are allowed to print any of them.

## Examples

### Input

```
3
-1 2 0

```

### Output

```
1 -1
1 2
1 0

```

### Input

```
4
-1 -2 -3 0

```

### Output

```
1 -1
2 -3 -2
1 0

```
