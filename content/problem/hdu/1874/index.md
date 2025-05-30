---
title: 【HDU】[1874]畅通工程续
type: post
slug: hdu-1874
categories:
  - hdu
ProblemParams:
    ProblemTitle: "畅通工程续"
    TimeLimit: "3000/1000 MS"
    MemoryLimit: "32768/32768 K"
---

## Problem Description

某省自从实行了很多年的畅通工程计划后，终于修建了很多路。不过路多了也不好，每次要从一个城镇到另一个城镇时，都有许多种道路方案可以选择，而某些方案要比另一些方案行走的距离要短很多。这让行人很困扰。  
  
现在，已知起点和终点，请你计算出要从起点到终点，最短需要行走多少距离。

## Input

本题目包含多组数据，请处理到文件结束。  
每组数据第一行包含两个正整数N和M(0<N<200,0<M<1000)，分别代表现有城镇的数目和已修建的道路的数目。城镇分别以0～N-1编号。  
接下来是M行道路信息。每一行有三个整数A,B,X(0<=A,B<N,A!=B,0<X<10000),表示城镇A和城镇B之间有一条长度为X的双向道路。  
再接下一行有两个整数S,T(0<=S,T<N)，分别代表起点和终点。

## Output

对于每组数据，请在一行里输出最短需要行走的距离。如果不存在从S到T的路线，就输出-1.

## Sample Input

```
3 3
0 1 1
0 2 3
1 2 1
0 2
3 1
0 1 1
1 2
```

## Sample Output

```
2
-1
```

## Author

linle

## Source

[2008浙大研究生复试热身赛（2）——全真模拟](https://acm.hdu.edu.cn//search.php?field=problem&key=2008%D5%E3%B4%F3%D1%D0%BE%BF%C9%FA%B8%B4%CA%D4%C8%C8%C9%ED%C8%FC%A3%A82%A3%A9%A1%AA%A1%AA%C8%AB%D5%E6%C4%A3%C4%E2&source=1&searchmode=source)
