---
title: 【DidaOJ】[1132]感恩节KK专场——考试来了
type: post
slug: didaoj-1132
categories:
  - didaoj
ProblemParams:
  ProblemTitle: "感恩节KK专场——考试来了"
  TimeLimit: "1000"
  MemoryLimit: "65536"
---

## 题目描述

很多课程马上就结课了，随之而来的就是可怕的考试啦。现在KK学长即将迎来n场考试，为了不挂科，他必须复习完这n门课程。

但是KK学长比较贪玩，一天只会花费a时间和b精力去复习。已知距离考试还有d天，问KK学长能不能复习完所有的功课。

## 输入

给定一个整数t，表示有t(t<=50)组测试数据。

每组测试数据第一行有一个整数n(1<=n<=100)，表示课程数目。 接下来一行有三个整数a，b，d(0<=a,b,d<=1000)，代表上面提到的信息。

下面有n行，每行有两个整数T[i]，E\[i\](0<=T\[i\],E\[i\]<=1000)，表示KK学长复习第i门课程，需要花费时间T[i]，消耗精力E[i]。

## 输出

若KK学长可以复习完所有的课程，输出YES，否则输出NO。输出占一行。

## 样例输入

```
1
5
2 3 4
1 1
1 1
1 1
1 1
1 1
```

## 样例输出

```
YES
```

