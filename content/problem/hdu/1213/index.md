---
title: 【HDU】[1213]How Many Tables
type: post
slug: hdu-1213
categories:
  - hdu
ProblemParams:
    ProblemTitle: "How Many Tables"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "65536/32768 K"
---

## Problem Description

Today is Ignatius' birthday. He invites a lot of friends. Now it's dinner time. Ignatius wants to know how many tables he needs at least. You have to notice that not all the friends know each other, and all the friends do not want to stay with strangers.  
  
One important rule for this problem is that if I tell you A knows B, and B knows C, that means A, B, C know each other, so they can stay in one table.  
  
For example: If I tell you A knows B, B knows C, and D knows E, so A, B, C can stay in one table, and D, E have to stay in the other one. So Ignatius needs 2 tables at least.

## Input

The input starts with an integer T(1<=T<=25) which indicate the number of test cases. Then T test cases follow. Each test case starts with two integers N and M(1<=N,M<=1000). N indicates the number of friends, the friends are marked from 1 to N. Then M lines follow. Each line consists of two integers A and B(A!=B), that means friend A and friend B know each other. There will be a blank line between two cases.

## Output

For each test case, just output how many tables Ignatius needs at least. Do NOT print any blanks.

## Sample Input

```
2
5 3
1 2
2 3
4 5

5 1
2 5

```

## Sample Output

```
2
4

```

## Author

Ignatius.L

## Source

[杭电ACM省赛集训队选拔赛之热身赛](https://acm.hdu.edu.cn//search.php?field=problem&key=%BA%BC%B5%E7ACM%CA%A1%C8%FC%BC%AF%D1%B5%B6%D3%D1%A1%B0%CE%C8%FC%D6%AE%C8%C8%C9%ED%C8%FC&source=1&searchmode=source)
