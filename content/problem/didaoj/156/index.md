---
title: 【DidaOJ】[156]DNA
type: post
slug: didaoj-156
categories:
  - didaoj
ProblemParams:
  ProblemTitle: "DNA"
  TimeLimit: "1000"
  MemoryLimit: "131072"
---

## 问题描述

<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">小强从小就喜欢生命科学，他总是好奇花草鸟兽从哪里来的。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">终于， 小强上中学了，接触到了神圣的名词——DNA。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">DNA有一个双螺旋的结构，</span><span style="font-family:'Microsoft YaHei';font-size:18px;line-height:1.5;">这让一根筋的小强抓破头皮，“要是能画出来就好了” ，小强喊道。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">现在就请你帮助他吧。</span> 
</p>

## 输入

<p style="text-indent:2em;">
	<span style="font-size:18px;line-height:27px;font-family:'Microsoft YaHei';">输入包含多组测试数据。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;line-height:27px;font-family:'Microsoft YaHei';">第一个整数$N$（$ N \leq 15 $）,$N$表示组数，每组数据包含两个整数$a$,$b$。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;line-height:27px;font-family:'Microsoft YaHei';">$a$表示一个单位的DNA串的行数，$a$为奇数且 $3 \leq a \leq 39$。</span> 
</p>
<p style="text-indent:2em;">
	<span style="font-size:18px;line-height:27px;font-family:'Microsoft YaHei';">$b$表示重复度($ 1 \leq b \leq 20 $)。</span> 
</p>

## 输出

<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">输出由大写X组成的DNA形状，每组输出间有一空行。</span> 
</p>

## 样例输入

```
2
3 1
5 4

```

## 样例输出

```
X X
 X
X X

X   X
 X X
  X
 X X
X   X
 X X
  X
 X X
X   X
 X X
  X
 X X
X   X
 X X
  X
 X X
X   X

```

## 提示
<p style="text-indent:2em;">
	<span style="font-size:18px;font-family:'Microsoft YaHei';">注意必须严格按照要求输出空行。</span> 
</p>
