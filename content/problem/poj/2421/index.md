---
title: 【POJ】[2421]Constructing Roads
type: post
slug: poj-2421
categories:
  - poj
ProblemParams:
    ProblemTitle: "Constructing Roads"
    TimeLimit: "2000MS"
    MemoryLimit: "65536K"
---

## Description

There are N villages, which are numbered from 1 to N, and you should build some roads such that every two villages can connect to each other. We say two village A and B are connected, if and only if there is a road between A and B, or there exists a village C such that there is a road between A and C, and C and B are connected.  
  
We know that there are already some roads between some villages and your job is the build some roads such that all the villages are connect and the length of all the roads built is minimum.

## Input

The first line is an integer N (3 <= N <= 100), which is the number of villages. Then come N lines, the i-th of which contains N integers, and the j-th of these N integers is the distance (the distance should be an integer within \[1, 1000\]) between village i and village j.  
  
Then there is an integer Q (0 <= Q <= N \* (N + 1) / 2). Then come Q lines, each line contains two integers a and b (1 <= a < b <= N), which means the road between village a and village b has been built.

## Output

The first line is an integer N (3 <= N <= 100), which is the number of villages. Then come N lines, the i-th of which contains N integers, and the j-th of these N integers is the distance (the distance should be an integer within \[1, 1000\]) between village i and village j.  
  
Then there is an integer Q (0 <= Q <= N \* (N + 1) / 2). Then come Q lines, each line contains two integers a and b (1 <= a < b <= N), which means the road between village a and village b has been built.

## Sample Input

```
3
0 990 692
990 0 179
692 179 0
1
1 2

```

## Sample Output

```
179
```

## Source

[PKU Monthly](http://poj.org/searchproblem?field=source&key=PKU+Monthly),kicc
