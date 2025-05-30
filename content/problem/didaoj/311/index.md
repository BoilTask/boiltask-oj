---
title: 【DidaOJ】[311]序列的区间操作
type: post
slug: didaoj-311
categories:
  - didaoj
ProblemParams:
  ProblemTitle: "序列的区间操作"
  TimeLimit: "2000"
  MemoryLimit: "262144"
---

## 问题描述

<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">给你[1, N]共N个数，和Q次操作，每次操作将区间[x, y]里面的数全加v。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">要求你按顺序输出Q次操作后这N个数。</span> 
</p>

## 输入

<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">有多组测试数据，请处理到文件结束。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">每组数据给定两个整数N和Q，接下来有Q行，表示Q次操作。每行有三个整数x、y、v。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">后台数据保证均满足 1 &lt;= N, Q &lt;= 10^7 且 1 &lt;= x &lt;= y &lt;= 10^7，1 &lt;= v &lt;= 10^7。</span> 
</p>

## 输出

<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">每组数据输出N个整数，每两个整数之间有一个空格，最后一个数后面没有空格。 </span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">由于最后的数可能比较大，你只需要输出% 666666的结果。</span> 
</p>

## 样例输入

```
1 1
1 1 3
2 2
1 1 3
2 2 1

```

## 样例输出

```
4
4 3

```
