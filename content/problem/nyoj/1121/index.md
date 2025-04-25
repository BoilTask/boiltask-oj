---
title: 【NYOJ】[1121]Triangular Sums
type: post
slug: nyoj-1121
categories:
  - nyoj
ProblemParams:
  ProblemTitle: "Triangular Sums"
  TimeLimit: "3000 MS"
  MemoryLimit: "256 MB"
---

## 题目描述

<span class="Apple-style-span" style="font-family:'Times New Roman', Times, serif;line-height:normal;font-size:16px;-webkit-border-horizontal-spacing:2px;-webkit-border-vertical-spacing:2px;"><p>The&nbsp;<b><i>n</i><sup>th</sup></b><i>&nbsp;Triangular</i>&nbsp;number,&nbsp;<b><i>T</i>(<i>n</i>) = 1 + … +&nbsp;<i>n</i></b>, is the sum of the first&nbsp;<b><i>n</i>&nbsp;</b>integers. It is the number of points in a triangular array with&nbsp;<b><i>n</i>&nbsp;</b>points on side. For example&nbsp;<b><i>T</i>(4)</b>:</p>
<b><div align="center">X<br />
X X<br />
X X X<br />
X X X X<br />
</div>
</b><p>Write a program to compute the weighted sum of triangular numbers:</p>
<p align="center"><b><i>W</i>(<i>n</i>) =&nbsp;<code>SUM[<i>k</i>&nbsp;= 1…<i>n</i>;&nbsp;<i>k</i>&nbsp;*&nbsp;<i>T</i>(<i>k</i>&nbsp;+ 1)]</code></b></p>
</span>

## 输入描述

The first line of input contains a single integer N, (1 ≤ N ≤ 1000) which is the number of datasets that follow.  
  
Each dataset consists of a single line of input containing a single integer n, (1 ≤ n ≤300), which is the number of points on a side of the triangle.

## 输出描述

For each dataset, output on a single line the dataset number (1 through N), a blank, the value of n for the dataset, a blank, and the weighted sum ,W(n), of triangular numbers for n.

## 用例

### 用例输入

```
4
3
4
5
10
```  

### 用例输出

```
1 3 45
2 4 105
3 5 210
4 10 2145
```

## 作者

张云聪

## 来源

NYOJ
