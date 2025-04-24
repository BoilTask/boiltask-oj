---
title: 【NYOJ】[1096]n-1位数
type: post
slug: nyoj-1096
categories:
  - nyoj
ProblemParams:
  ProblemTitle: "n-1位数"
  TimeLimit: "3000 MS"
  MemoryLimit: "256 MB"
---

## 题目描述

已知w是一个大于10但不大于1000000的无符号整数，若w是n(n≥2)位的整数，则求出w的后n-1位的数。

## 输入描述

第一行为M，表示测试数据组数。  
接下来M行，每行包含一个测试数据。

## 输出描述

输出M行，每行为对应行的n-1位数（忽略前缀0）。如果除了最高位外，其余位都为0，则输出0。

## 用例

### 用例输入

```
4
1023
5923
923
1000
```  

### 用例输出

```
23
923
23
0
```

## 作者

rooot

## 来源

NYOJ
