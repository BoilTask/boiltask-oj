---
title: 【HDU】[5645]DZY Loves Balls
type: post
slug: hdu-5645
categories:
  - hdu
ProblemParams:
    ProblemTitle: "DZY Loves Balls"
    TimeLimit: "4000/2000 MS"
    MemoryLimit: "262144/262144 K"
---

## Problem Description

DZY loves playing balls.  
  
He has $n$ balls in a big box. On each ball there is an integer written.  
  
One day he decides to pick two balls from the box. First he randomly picks a ball from the box, and names it $A$. Next, without putting $A$ back into the box, he randomly picks another ball from the box, and names it $B$.  
  
If the number written on $A$ is strictly greater than the number on $B$, he will feel happy.  
  
Now you are given the numbers on each ball. Please calculate the probability that he feels happy.

## Input

First line contains $t$ denoting the number of testcases.  
  
$t$ testcases follow. In each testcase, first line contains $n$, second line contains $n$ space-separated positive integers $a\_i$, denoting the numbers on the balls.  
  
($1\\le t\\le 300, 2\\le n \\le 300,1\\le a\_i \\le 300$)

## Output

For each testcase, output a real number with 6 decimal places.

## Sample Input

```
2
3
1 2 3
3
100 100 100

```

## Sample Output

```
0.500000
0.000000

```

## Source

[BestCoder Round #76 (div.2)](https://acm.hdu.edu.cn//search.php?field=problem&key=BestCoder+Round+%2376+%28div.2%29&source=1&searchmode=source)
