---
title: 【HDU】[5777]domino
type: post
slug: hdu-5777
categories:
  - hdu
ProblemParams:
    ProblemTitle: "domino"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "131072/131072 K"
---

## Problem Description

Little White plays a game.There are n pieces of dominoes on the table in a row. He can choose a domino which hasn't fall down for at most k times, let it fall to the left or right. When a domino is toppled, it will knock down the erect domino. On the assumption that all of the tiles are fallen in the end, he can set the height of all dominoes, but he wants to minimize the sum of all dominoes height. The height of every domino is an integer and at least 1.

## Input

The first line of input is an integer T ( $1 \\leq T \\leq 10 $)  
There are two lines of each test case.  
The first line has two integer n and k, respectively domino number and the number of opportunities.( $2\\leq k, n \\leq 100000 $)  
The second line has n - 1 integers, the distance of adjacent domino d, $1 \\leq d \\leq 100000 $

## Output

For each testcase, output of a line, the smallest sum of all dominoes height

## Sample Input

```
1
4 2
2 3 4
```

## Sample Output

```
9
```

## Source

[BestCoder Round #85](https://acm.hdu.edu.cn//search.php?field=problem&key=BestCoder+Round+%2385&source=1&searchmode=source)
