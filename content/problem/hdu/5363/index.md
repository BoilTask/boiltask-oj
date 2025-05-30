---
title: 【HDU】[5363]Key Set
type: post
slug: hdu-5363
categories:
  - hdu
ProblemParams:
    ProblemTitle: "Key Set"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "131072/131072 K"
---

## Problem Description

soda has a set $S$ with $n$ integers $\\{1, 2, \\dots, n\\}$. A set is called key set if the sum of integers in the set is an even number. He wants to know how many nonempty subsets of $S$ are key set.

## Input

There are multiple test cases. The first line of input contains an integer $T$ $(1 \\le T \\le 10^5)$, indicating the number of test cases. For each test case:  
  
The first line contains an integer $n$ $(1 \\le n \\le 10^9)$, the number of integers in the set.

## Output

For each test case, output the number of key sets modulo 1000000007.

## Sample Input

```
4
1
2
3
4
```

## Sample Output

```
0
1
3
7
```

## Author

zimpha@zju

## Source

[2015 Multi-University Training Contest 6](https://acm.hdu.edu.cn//search.php?field=problem&key=2015+Multi-University+Training+Contest+6&source=1&searchmode=source)
