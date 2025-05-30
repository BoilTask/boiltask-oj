---
title: 【DidaOJ】[306]神奇的数字9
type: post
slug: didaoj-306
categories:
  - didaoj
ProblemParams:
  ProblemTitle: "神奇的数字9"
  TimeLimit: "1000"
  MemoryLimit: "131072"
---

## 问题描述

<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">给定一个数N(没有前导0)和Q次操作，每次操作修改第i位数字 为 v(保证不会把第一位修改为0)，对每次操作判定新数能否被9整除。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">若满足被9整除输出1，反之输出0。</span> 
</p>

## 输入

<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">有多组测试数据，请处理到文件结束。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">每组数据有两个整数N和Q，接下来有Q行代表Q次操作，每行有两个整数i和v。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">后台数据保证0 &lt;= N &lt;= 10^1000000，1 &lt;= Q &lt;= 10^6，1 &lt;= i &lt;= |N|，0 &lt;= v &lt;= 9。</span> 
</p>

## 输出

<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">每组数据输出Q行，代表对Q次操作后的判定。</span> 
</p>

## 样例输入

```
999 3
2 0
3 0
2 9
10000000000000000000000000000000000000000000000 1
2 8
10000000000000000000000000000000000000000000000 4
2 9
3 8
4 9
5 9

```

## 样例输出

```
1
1
1
1
0
1
1
1

```
