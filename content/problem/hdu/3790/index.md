---
title: 【HDU】[3790]最短路径问题
type: post
slug: hdu-3790
categories:
  - hdu
ProblemParams:
    ProblemTitle: "最短路径问题"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "32768/32768 K"
---

## Problem Description

给你n个点，m条无向边，每条边都有长度d和花费p，给你起点s终点t，要求输出起点到终点的最短距离及其花费，如果最短距离有多条路线，则输出花费最少的。

## Input

输入n,m，点的编号是1~n,然后是m行，每行4个数 a,b,d,p，表示a和b之间有一条边，且其长度为d，花费为p。最后一行是两个数 s,t;起点s，终点。n和m为0时输入结束。  
(1<n<=1000, 0<m<100000, s != t)

## Output

输出 一行有两个数， 最短距离及其花费。

## Sample Input

```
3 2
1 2 5 6
2 3 4 5
1 3
0 0
```

## Sample Output

```
9 11
```

## Source

[浙大计算机研究生复试上机考试-2010年](https://acm.hdu.edu.cn//search.php?field=problem&key=%D5%E3%B4%F3%BC%C6%CB%E3%BB%FA%D1%D0%BE%BF%C9%FA%B8%B4%CA%D4%C9%CF%BB%FA%BF%BC%CA%D4-2010%C4%EA&source=1&searchmode=source)
