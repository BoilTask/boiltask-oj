---
title: 【HDU】[2073]无限的路
type: post
slug: hdu-2073
categories:
  - hdu
ProblemParams:
    ProblemTitle: "无限的路"
    TimeLimit: "1000/1000 MS"
    MemoryLimit: "32768/32768 K"
---

## Problem Description

甜甜从小就喜欢画图画，最近他买了一支智能画笔，由于刚刚接触，所以甜甜只会用它来画直线，于是他就在平面直角坐标系中画出如下的图形：  
  
<div style="text-align: center;"><img style="max-width:100%;" src="https://r2-oj.boiltask.com/hdu-2073/d3015e28cc1b105b3c78a385c8702144"></div>  
  
甜甜的好朋友蜜蜜发现上面的图还是有点规则的，于是他问甜甜：在你画的图中，我给你两个点，请你算一算连接两点的折线长度（即沿折线走的路线长度）吧。

## Input

第一个数是正整数N（≤100）。代表数据的组数。  
每组数据由四个非负整数组成x1，y1，x2，y2；所有的数都不会大于100。

## Output

对于每组数据，输出两点(x1,y1),(x2,y2)之间的折线距离。注意输出结果精确到小数点后3位。

## Sample Input

```
5
0 0 0 1
0 0 1 0
2 3 3 1
99 99 9 9
5 5 5 5

```

## Sample Output

```
1.000
2.414
10.646
54985.047
0.000

```

## Author

Lily

## Source

[浙江工业大学网络选拔赛](https://acm.hdu.edu.cn//search.php?field=problem&key=%D5%E3%BD%AD%B9%A4%D2%B5%B4%F3%D1%A7%CD%F8%C2%E7%D1%A1%B0%CE%C8%FC&source=1&searchmode=source)
