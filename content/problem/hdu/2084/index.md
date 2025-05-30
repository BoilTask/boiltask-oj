---
title: 【HDU】[2084]数塔
type: post
slug: hdu-2084
categories:
  - hdu
ProblemParams:
    ProblemTitle: "数塔"
    TimeLimit: "1000/1000 MS"
    MemoryLimit: "32768/32768 K"
---

## Problem Description

在讲述DP算法的时候，一个经典的例子就是数塔问题，它是这样描述的：  
  
有如下所示的数塔，要求从顶层走到底层，若每一步只能走到相邻的结点，则经过的结点的数字之和最大是多少？  
![](https://r2-oj.boiltask.com/hdu-2084/af7dffec83b94a90a248e4604d5a6d45)  
已经告诉你了，这是个DP的题目，你能AC吗?

## Input

输入数据首先包括一个整数C,表示测试实例的个数，每个测试实例的第一行是一个整数N(1 <= N <= 100)，表示数塔的高度，接下来用N行数字表示数塔，其中第i行有个i个整数，且所有的整数均在区间\[0,99\]内。

## Output

对于每个测试实例，输出可能得到的最大和，每个实例的输出占一行。

## Sample Input

```
1
5
7
3 8
8 1 0 
2 7 4 4
4 5 2 6 5

```

## Sample Output

```
30

```

## Source

[2006/1/15 ACM程序设计期末考试](https://acm.hdu.edu.cn//search.php?field=problem&key=2006%2F1%2F15+ACM%B3%CC%D0%F2%C9%E8%BC%C6%C6%DA%C4%A9%BF%BC%CA%D4&source=1&searchmode=source)
