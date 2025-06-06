---
title: 【NYOJ】[1840]取石子（九）
type: post
slug: nyoj-1840
categories:
  - nyoj
ProblemParams:
  ProblemTitle: "取石子（九）"
  TimeLimit: "1000 MS"
  MemoryLimit: "256 MB"
---

## 题目描述

最近TopCoder的Yougth和Hrdv在玩一个游戏，游戏是这样的。

有n堆石子,两个人轮流从其中某一堆中任意取走一定的石子,最后不能取的为赢家，注意： 每次只能从一堆取任意个，可以取完这堆，但不能不取。

假设Yougth先取，输入赢了的人名字、

## 输入描述

第一行输入n，代表有n组测试数据(n<=10000)  
以下每组测试数据包含两行：第一行：包含一个整数m，代表本组测试数据有m（m<=1000）堆石子；  
：第二行：包含m个整数Ai(Ai<=10000)，分别代表第i堆石子的数量。

## 输出描述

若Yougth赢输出“Yougth”，否则输出“Hrdv”注意每组结果占一行。。

## 用例

### 用例输入

```
3
2
1 1
3
3 8 11
2
5 10
```
  

### 用例输出

```
Yougth
Hrdv
Yougth
```

## 作者

TC\_杨闯亮

## 来源

NYOJ
