---
title: 【POJ】[1258]Agri-Net
type: post
slug: poj-1258
categories:
  - poj
ProblemParams:
    ProblemTitle: "Agri-Net"
    TimeLimit: "1000MS"
    MemoryLimit: "10000K"
---

## Description

Farmer John has been elected mayor of his town! One of his campaign promises was to bring internet connectivity to all farms in the area. He needs your help, of course.  
Farmer John ordered a high speed connection for his farm and is going to share his connectivity with the other farmers. To minimize cost, he wants to lay the minimum amount of optical fiber to connect his farm to all the other farms.  
Given a list of how much fiber it takes to connect each pair of farms, you must find the minimum amount of fiber needed to connect them all together. Each farm must connect to some other farm such that a packet can flow from any one farm to any other farm.  
The distance between any two farms will not exceed 100,000.

## Input

The input includes several cases. For each case, the first line contains the number of farms, N (3 <= N <= 100). The following lines contain the N x N conectivity matrix, where each element shows the distance from on farm to another. Logically, they are N lines of N space-separated integers. Physically, they are limited in length to 80 characters, so some lines continue onto others. Of course, the diagonal will be 0, since the distance from farm i to itself is not interesting for this problem.

## Output

The input includes several cases. For each case, the first line contains the number of farms, N (3 <= N <= 100). The following lines contain the N x N conectivity matrix, where each element shows the distance from on farm to another. Logically, they are N lines of N space-separated integers. Physically, they are limited in length to 80 characters, so some lines continue onto others. Of course, the diagonal will be 0, since the distance from farm i to itself is not interesting for this problem.

## Sample Input

```
4
0 4 9 21
4 0 8 17
9 8 0 16
21 17 16 0

```

## Sample Output

```
28
```

## Source

[USACO 102](https://web.archive.org/web/http://poj.org/searchproblem?field=source&key=USACO+102)
