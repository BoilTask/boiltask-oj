---
title: 【HDU】[1254]推箱子
type: post
slug: hdu-1254
categories:
  - hdu
ProblemParams:
    ProblemTitle: "推箱子"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "65536/32768 K"
---

## Problem Description

推箱子是一个很经典的游戏.今天我们来玩一个简单版本.在一个M\*N的房间里有一个箱子和一个搬运工,搬运工的工作就是把箱子推到指定的位置,注意,搬运工只能推箱子而不能拉箱子,因此如果箱子被推到一个角上(如图2)那么箱子就不能再被移动了,如果箱子被推到一面墙上,那么箱子只能沿着墙移动.  
  
现在给定房间的结构,箱子的位置,搬运工的位置和箱子要被推去的位置,请你计算出搬运工至少要推动箱子多少格.  
  
<div style="text-align: center;"><img style="max-width:100%;" src="https://r2-oj.boiltask.com/hdu-1254/8bafdac83d574d0b402773ac9a1ddc29"></div>

## Input

输入数据的第一行是一个整数T(1<=T<=20),代表测试数据的数量.然后是T组测试数据,每组测试数据的第一行是两个正整数M,N(2<=M,N<=7),代表房间的大小,然后是一个M行N列的矩阵,代表房间的布局,其中0代表空的地板,1代表墙,2代表箱子的起始位置,3代表箱子要被推去的位置,4代表搬运工的起始位置.

## Output

对于每组测试数据,输出搬运工最少需要推动箱子多少格才能帮箱子推到指定位置,如果不能推到指定位置则输出-1.

## Sample Input

```
1
5 5
0 3 0 0 0
1 0 1 4 0
0 0 1 0 0
1 0 2 0 0
0 0 0 0 0

```

## Sample Output

```
4

```

## Author

Ignatius.L & weigang Lee
