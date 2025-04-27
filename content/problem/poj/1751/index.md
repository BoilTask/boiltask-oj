---
title: 【POJ】[1751]Highways
type: post
slug: poj-1751
categories:
  - poj
ProblemParams:
    ProblemTitle: "Highways"
    TimeLimit: "1000MS"
    MemoryLimit: "10000K"
---

## Description

The island nation of Flatopia is perfectly flat. Unfortunately, Flatopia has a very poor system of public highways. The Flatopian government is aware of this problem and has already constructed a number of highways connecting some of the most important towns. However, there are still some towns that you can't reach via a highway. It is necessary to build more highways so that it will be possible to drive between any pair of towns without leaving the highway system.  
  
Flatopian towns are numbered from 1 to N and town i has a position given by the Cartesian coordinates (xi, yi). Each highway connects exaclty two towns. All highways (both the original ones and the ones that are to be built) follow straight lines, and thus their length is equal to Cartesian distance between towns. All highways can be used in both directions. Highways can freely cross each other, but a driver can only switch between highways at a town that is located at the end of both highways.  
  
The Flatopian government wants to minimize the cost of building new highways. However, they want to guarantee that every town is highway-reachable from every other town. Since Flatopia is so flat, the cost of a highway is always proportional to its length. Thus, the least expensive highway system will be the one that minimizes the total highways length.

## Input

The input consists of two parts. The first part describes all towns in the country, and the second part describes all of the highways that have already been built.  
  
The first line of the input file contains a single integer N (1 <= N <= 750), representing the number of towns. The next N lines each contain two integers, xi and yi separated by a space. These values give the coordinates of ith town (for i from 1 to N). Coordinates will have an absolute value no greater than 10000. Every town has a unique location.  
  
The next line contains a single integer M (0 <= M <= 1000), representing the number of existing highways. The next M lines each contain a pair of integers separated by a space. These two integers give a pair of town numbers which are already connected by a highway. Each pair of towns is connected by at most one highway.

## Output

The input consists of two parts. The first part describes all towns in the country, and the second part describes all of the highways that have already been built.  
  
The first line of the input file contains a single integer N (1 <= N <= 750), representing the number of towns. The next N lines each contain two integers, xi and yi separated by a space. These values give the coordinates of ith town (for i from 1 to N). Coordinates will have an absolute value no greater than 10000. Every town has a unique location.  
  
The next line contains a single integer M (0 <= M <= 1000), representing the number of existing highways. The next M lines each contain a pair of integers separated by a space. These two integers give a pair of town numbers which are already connected by a highway. Each pair of towns is connected by at most one highway.

## Sample Input

```
9
1 5
0 0 
3 2
4 5
5 1
0 4
5 2
1 2
5 3
3
1 3
9 7
1 2
```

## Sample Output

```
1 6
3 7
4 9
5 7
8 3

```

## Source

[Northeastern Europe 1999](http://poj.org/searchproblem?field=source&key=Northeastern+Europe+1999)
