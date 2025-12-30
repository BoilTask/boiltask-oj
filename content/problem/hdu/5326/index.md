---
title: 【HDU】[5326]Work
type: post
slug: hdu-5326
categories:
  - hdu
ProblemParams:
    ProblemTitle: "Work"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "32768/32768 K"
---

## Problem Description

<div style="text-align: center;"><img style="max-width:100%;" src="https://r2-oj.boiltask.com/hdu-5326/63dd64f7573005aea4a2ea707e65afb5"></div>  
  
It’s an interesting experience to move from ICPC to work, end my college life and start a brand new journey in company.  
As is known to all, every stuff in a company has a title, everyone except the boss has a direct leader, and all the relationship forms a tree. If A’s title is higher than B(A is the direct or indirect leader of B), we call it A manages B.  
Now, give you the relation of a company, can you calculate how many people manage k people.

## Input

There are multiple test cases.  
Each test case begins with two integers n and k, n indicates the number of stuff of the company.  
Each of the following n-1 lines has two integers A and B, means A is the direct leader of B.  
  
1 <= n <= 100 , 0 <= k < n  
1 <= A, B <= n

## Output

For each test case, output the answer as described above.

## Sample Input

```
7 2
1 2
1 3
2 4
2 5
3 6
3 7

```

## Sample Output

```
2
```

## Author

ZSTU

## Source

[2015 Multi-University Training Contest 3](https://acm.hdu.edu.cn//search.php?field=problem&key=2015+Multi-University+Training+Contest+3&source=1&searchmode=source)
