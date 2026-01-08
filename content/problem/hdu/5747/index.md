---
title: 【HDU】[5747]Aaronson
type: post
slug: hdu-5747
categories:
  - hdu
ProblemParams:
    ProblemTitle: "Aaronson"
    TimeLimit: "4000/2000 MS"
    MemoryLimit: "131072/131072 K"
---

## Problem Description

Recently, Peter saw the equation $x\_{0}+2x\_{1}+4x\_{2}+...+2^{m}x\_{m}=n$. He wants to find a solution $(x\_0,x\_1,x\_2,...,x\_m)$ in such a manner that $\\displaystyle\\sum\_{i=0}^{m} x\_i$ is minimum and every $x\_i$ ($0 \\le i \\le m$) is non-negative.

## Input

There are multiple test cases. The first line of input contains an integer $T$ $(1 \\le T \\le 10^5)$, indicating the number of test cases. For each test case:  
  
The first contains two integers $n$ and $m$ $(0 \\le n,m \\le 10^9)$.

## Output

For each test case, output the minimum value of $\\displaystyle\\sum\_{i=0}^{m} x\_i$.

## Sample Input

```
10
1 2
3 2
5 2
10 2
10 3
10 4
13 5
20 4
11 11
12 3
```

## Sample Output

```
1
2
2
3
2
2
3
2
3
2
```

## Source

[BestCoder Round #84](https://acm.hdu.edu.cn//search.php?field=problem&key=BestCoder+Round+%2384&source=1&searchmode=source)
