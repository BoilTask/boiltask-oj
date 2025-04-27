---
title: 【POJ】[1328]Radar Installation
type: post
slug: poj-1328
categories:
  - poj
ProblemParams:
    ProblemTitle: "Radar Installation"
    TimeLimit: "1000MS"
    MemoryLimit: "10000K"
---

## Description

Assume the coasting is an infinite straight line. Land is in one side of coasting, sea in the other. Each small island is a point locating in the sea side. And any radar installation, locating on the coasting, can only cover d distance, so an island in the sea can be covered by a radius installation, if the distance between them is at most d.  
  
We use Cartesian coordinate system, defining the coasting is the x-axis. The sea side is above x-axis, and the land side below. Given the position of each island in the sea, and given the distance of the coverage of the radar installation, your task is to write a program to find the minimal number of radar installations to cover all the islands. Note that the position of an island is represented by its x-y coordinates.  
<div style="text-align: center;"><img src="https://r2-oj.boiltask.com/poj-1328/272066dd8972370d669478190f464ec4"><br>Figure A Sample Input of Radar Installations</div>

## Input

The input consists of several test cases. The first line of each case contains two integers n (1<=n<=1000) and d, where n is the number of islands in the sea and d is the distance of coverage of the radar installation. This is followed by n lines each containing two integers representing the coordinate of the position of each island. Then a blank line follows to separate the cases.  
  
The input is terminated by a line containing pair of zeros

## Output

The input consists of several test cases. The first line of each case contains two integers n (1<=n<=1000) and d, where n is the number of islands in the sea and d is the distance of coverage of the radar installation. This is followed by n lines each containing two integers representing the coordinate of the position of each island. Then a blank line follows to separate the cases.  
  
The input is terminated by a line containing pair of zeros

## Sample Input

```
3 2
1 2
-3 1
2 1

1 2
0 2

0 0

```

## Sample Output

```
Case 1: 2
Case 2: 1

```

## Source

[Beijing 2002](http://poj.org/searchproblem?field=source&key=Beijing+2002)
