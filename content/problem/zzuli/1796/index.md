---
title: 【ZZULI】[1796]两人之间的距离
type: post
slug: zzuli-1796
categories:
  - zzuli
ProblemParams:
  ProblemTitle: "两人之间的距离"
  TimeLimit: "1 Sec"
  MemoryLimit: "128 MB"
---

## 题目描述

在一个半径为r圆形跑道上， A、B两人在同一个点同一时刻出发，分别以va、vb的速度反向行进，问在时刻tA、B之间在跑道上的最近距离。  
本题要求定义一个函数计算A、B之间的距离，函数原型如下：  
double distance(int r,int va,int vb,int t);  
函数返回值为A、B之间在跑道上的最近距离。  
  
**注意：本题要求提交完整程序，并且必须通过定义distance函数来实现计算A、B之间的距离。**  
**圆周率PI的值为3.14159**

## 输入

本题为多实例  
每个实例输入占一行，包括四个整数r,va,vb,t(0<r,va,vb,t<1000).

## 输出

针对每个测试实例输出一个实数，表示A、B之间的最近距离，保留两位小数。

## 样例输入

```
1 1 1 1
1 2 2 2
```

## 样例输出

```
2.00
1.72
```

## 来源/分类

[](https://web.archive.org/web/http://acm.zzuli.edu.cn/problemset.php?search=)
