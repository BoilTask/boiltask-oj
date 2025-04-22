---
title: 【ZZULI】[1802]SC借水
type: post
slug: zzuli-1802
categories:
  - zzuli
ProblemParams:
  ProblemTitle: "SC借水"
  TimeLimit: "1 Sec"
  MemoryLimit: "128 MB"
---

## 题目描述

一天，住在3号楼的SC向住在X号楼的WT借水喝，机智的WT会每隔K秒给SC倒一滴水

现在SC有一个容量为V的大杯子（可以装V滴水）

WT从1时刻开始计时，请问受众多女孩子追捧的SC在\[S, E\]这个时间段里可以用他的大杯子接到多少滴水？

## 输入

第一行一个正整数T（T <= 1000），表示有T组数据。

接下来每组数据占一行，每一行有四个整数V，K，S，E。（1 <= S <= E <= 10^9， 1 <= V <= 10^9，1 <= K <= 10^9）

## 输出

对每组输入，输出用杯子最多接多少滴水，单独占一行。

## 样例输入

```
3
1 1 1 1
10 3 1 9
10 2 5 9
```

## 样例输出

```
1
3
2
```

## 提示

对于第三组数据，WT会分别在2、4、6、8、10、12……时刻滴一滴水，而SC接水的区间里只有6、8，所以SC可以接到2滴水。

## 来源/分类

[SC的日常](https://web.archive.org/web/http://acm.zzuli.edu.cn/problemset.php?search=SC%E7%9A%84%E6%97%A5%E5%B8%B8)
