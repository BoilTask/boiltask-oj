---
title: 【DidaOJ】[283]Stack ？ Queue ？
type: post
slug: didaoj-283
categories:
  - didaoj
ProblemParams:
  ProblemTitle: "Stack ？ Queue ？"
  TimeLimit: "1000"
  MemoryLimit: "131072"
---

## 问题描述

<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">给定n个元素的输入顺序和输出顺序，需要你判定这是一个栈还是队列？</span> 
</p>

## 输入

<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">有多组测试数据。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">每组数据第一行有一个整数n，表示元素个数。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">第二行有n个整数，表示输入顺序，第三行有n个整数，表示输出顺序。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">后台数据保证2 &lt;= n &lt;= 10，给定的n个元素均不相同。</span> 
</p>

## 输出

<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">若有可能是一个队列的操作，则输出0。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">若是一个栈的操作，则输出1。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">数据保证有解。</span> 
</p>

## 样例输入

```
2
1 2
2 1
3
2 1 3
2 3 1
3
1 2 3
1 2 3

```

## 样例输出

```
1
1
0

```
