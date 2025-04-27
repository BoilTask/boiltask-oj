---
title: 【POJ】[2485]Highways
type: post
slug: poj-2485
categories:
  - poj
ProblemParams:
    ProblemTitle: "Highways"
    TimeLimit: "1000MS"
    MemoryLimit: "65536K"
---

## Description

The island nation of Flatopia is perfectly flat. Unfortunately, Flatopia has no public highways. So the traffic is difficult in Flatopia. The Flatopian government is aware of this problem. They're planning to build some highways so that it will be possible to drive between any pair of towns without leaving the highway system.  
  
Flatopian towns are numbered from 1 to N. Each highway connects exactly two towns. All highways follow straight lines. All highways can be used in both directions. Highways can freely cross each other, but a driver can only switch between highways at a town that is located at the end of both highways.  
  
The Flatopian government wants to minimize the length of the longest highway to be built. However, they want to guarantee that every town is highway-reachable from every other town.

## Input

The first line of input is an integer T, which tells how many test cases followed.  
The first line of each case is an integer N (3 <= N <= 500), which is the number of villages. Then come N lines, the i-th of which contains N integers, and the j-th of these N integers is the distance (the distance should be an integer within \[1, 65536\]) between village i and village j. There is an empty line after each test case.

## Output

The first line of input is an integer T, which tells how many test cases followed.  
The first line of each case is an integer N (3 <= N <= 500), which is the number of villages. Then come N lines, the i-th of which contains N integers, and the j-th of these N integers is the distance (the distance should be an integer within \[1, 65536\]) between village i and village j. There is an empty line after each test case.

## Sample Input

```
1

3
0 990 692
990 0 179
692 179 0
```

## Sample Output

```
692

```

## Hint

Huge input,scanf is recommended.

## Source

[POJ Contest](http://poj.org/searchproblem?field=source&key=POJ+Contest),Author:Mathematica@ZSU
