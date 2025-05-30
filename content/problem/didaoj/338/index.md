---
title: 【DidaOJ】[338]QAQ的问题
type: post
slug: didaoj-338
categories:
  - didaoj
ProblemParams:
  ProblemTitle: "QAQ的问题"
  TimeLimit: "1000"
  MemoryLimit: "131072"
---

## 问题描述

<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">有M个不同的阵地，每个阵地上可以留守任意个士兵(为非负数)。现在QAQ有N个士兵，他需要选择至少一个阵地才可以获得胜利。QAQ的一贯原则——让所有士兵留守在他选择的阵地上。问有多少种安排方案使得QAQ获得胜利。为了降低难度，QAQ在选择的阵地上不留守士兵也是合法的。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">方案数的不同判定只能依据下面三条：</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">(1)选择的阵地数目不同</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">——选择1个阵地和选择2个阵地。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">(2)选择的阵地不同</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">——选择阵地1、2和选择阵地2、3。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">(3)在选择的阵地中任意两个阵地留守士兵数目不同</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">——阵地1有a人、阵地2有b人；阵地1有c人、阵地2有d人。其中a != c || b != d 且a、b、c、d均为非负数。</span> 
</p>
<p style="text-indent:2em;">
	<br />
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">举个例子：有2个士兵和2个阵地，方案数为5。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">(1)选择1个阵地方案数为2 —— 选择阵地1并留守2个士兵 或者 选择阵地2并留守2个士兵。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">(2)选择2个阵地方案数为3 —— 在阵地1、2留守士兵人数为0 2、2 0、1 1。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">这里要注意：不能依据每个阵地的人数来判定(1)里面的方案2 !0、!0 2和(2)的2 0、 0 2重复，因为前提选择的阵地数目不同。</span> 
</p>

## 输入

<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">有多组测试数据，请处理到文件结束。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">每组数据给定两个整数N和M，分别表示士兵人数和阵地数目。1 &lt;= N, M &lt;= 50。</span> 
</p>

## 输出

<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">每组数据输出一个整数表示不同的方案数。由于结果可能很大，你只需要输出 % 777的结果。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">解释一下，如果最后结果为777，你只需要输出777 % 777 = 0。</span> 
</p>

## 样例输入

```
2 2
46 37
1 1

```

## 样例输出

```
5
0
1

```
