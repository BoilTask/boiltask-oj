---
title: 【DidaOJ】[1147]老王特警队
type: post
slug: didaoj-1147
categories:
  - didaoj
ProblemParams:
  ProblemTitle: "老王特警队"
  TimeLimit: "1000"
  MemoryLimit: "131072"
---

<p><span style="font-size: small"><span style="font-family: Verdana">公园终于修完了，在家休假的老王接到上峰的命令，要配合武装力量打击毒贩的巢穴。老王一秒<br />
变身为特警队员。毒贩藏匿在一个复杂的，近乎迷宫的废弃工厂里。如下地图：<br />
0,0,1,1,1,1,1,1,1<br />
1,0,0,1,0,0,1,0,1<br />
1,0,0,1,1,0,0,0,1<br />
1,0,1,0,1,1,0,1,1<br />
1,0,0,0,0,1,0,0,1<br />
1,1,0,1,0,1,0,0,1<br />
1,1,0,1,0,1,0,0,1<br />
1,1,0,1,0,0,0,0,1<br />
0,1,1,1,1,1,1,0,0</span></span></p>
<p><span style="font-size: small"><span style="font-family: Verdana">坐标（0&lt;=x&lt;=8）(0&lt;=y&lt;=8)</span></span></p>
<p><span style="font-size: small"><span style="font-family: Verdana">&ldquo;0&rdquo;表示道路，&ldquo;1&rdquo;表示墙。在迷宫中，只能上下左右移动。现在给出老王所在的位置和毒贩藏匿的<br />
位置，你帮助老王计算最少需要多少步到达毒贩藏匿的位置。</span></span></p>

## 输入
<p><span style="font-size: small"><span style="font-family: Verdana">第一行输入一个T，表示有T组测试数据。随后T行中每行给出x1,y1,x2,y2，分别表示起点的坐标和终点的坐标。</span></span></p>

## 输出
<p><span style="font-size: small"><span style="font-family: Verdana">输出最少的步数，若到达不了，输出&ldquo;LaoWang fail&rdquo; 。</span></span></p>

## 样例输入
```
3
3 1 5 7
3 1 6 7
0 0 8 0
```


## 样例输出
```
12
11
LaoWang fail
```

