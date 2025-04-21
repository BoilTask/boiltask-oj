---
title: 【ZZULI】[1724]candy
type: post
slug: zzuli-1724
categories:
  - zzuli
ProblemParams:
  ProblemTitle: "candy"
  TimeLimit: "3 Sec"
  MemoryLimit: "128 MB"
---

## 题目描述

Kimi has a lot of candies, and divides them into piles, where the _i_th pile contains _A__i_ candies. Each time Kimi will choose an interval \[_l_,_r_\], and calculate the total amount of _A__l_,_A__l_+1,…,_A__r_. It's a hard task, and you're required to solve it.

## 输入

An integer _T_(_T_≤10) will exist in the first line of input, indicating the number of test cases. Each test case begins with the number of piles _N_(1≤_N_≤105). The second line contains _N_ integers _A__i_(1≤_A__i_≤100), where _A__i_ stands for the number of candies in the _i_th pile. The next line is the number of queries _M_(1≤_M_≤105). The next _M_ lines, each with two integers _l_,_r_(1≤_l_≤_r_≤_N_), describe the queried intervals.

## 输出

For each test case, output the total amount of candies in the queried interval.

## 样例输入

```
1
5
1 2 4 5 9
3
1 2
2 4
4 5
```

## 样例输出

```
3
11
14
```

## 来源/分类

[](https://web.archive.org/web/http://acm.zzuli.edu.cn/problemset.php?search=)
