---
title: 【HDU】[1576]A/B
type: post
slug: hdu-1576
categories:
  - hdu
ProblemParams:
    ProblemTitle: "A/B"
    TimeLimit: "1000/1000 MS"
    MemoryLimit: "32768/32768 K"
---

## Problem Description

要求(A/B)%9973，但由于A很大，我们只给出n(n=A%9973)(我们给定的A必能被B整除，且gcd(B,9973) = 1)。

## Input

数据的第一行是一个T，表示有T组数据。  
每组数据有两个数n(0 <= n < 9973)和B(1 <= B <= 10^9)。

## Output

对应每组数据输出(A/B)%9973。

## Sample Input

```
2
1000 53
87 123456789
```

## Sample Output

```
7922
6060
```

## Author

xhd

## Source

[HDU 2007-1 Programming Contest](https://acm.hdu.edu.cn//search.php?field=problem&key=HDU+2007-1+Programming+Contest&source=1&searchmode=source)
