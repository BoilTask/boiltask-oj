---
title: 【HDU】[1878]欧拉回路
type: post
slug: hdu-1878
categories:
  - hdu
ProblemParams:
    ProblemTitle: "欧拉回路"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "32768/32768 K"
---

## Problem Description

欧拉回路是指不令笔离开纸面，可画过图中每条边仅一次，且可以回到起点的一条回路。现给定一个图，问是否存在欧拉回路？

## Input

测试输入包含若干测试用例。每个测试用例的第1行给出两个正整数，分别是节点数N ( 1 < N < 1000 )和边数M；随后的M行对应M条边，每行给出一对正整数，分别是该条边直接连通的两个节点的编号（节点从1到N编号）。当N为0时输入结  
束。

## Output

每个测试用例的输出占一行，若欧拉回路存在则输出1，否则输出0。

## Sample Input

```
3 3
1 2
1 3
2 3
3 2
1 2
2 3
0

```

## Sample Output

```
1
0
```

## Author

ZJU

## Source

[浙大计算机研究生复试上机考试-2008年](https://acm.hdu.edu.cn//search.php?field=problem&key=%D5%E3%B4%F3%BC%C6%CB%E3%BB%FA%D1%D0%BE%BF%C9%FA%B8%B4%CA%D4%C9%CF%BB%FA%BF%BC%CA%D4-2008%C4%EA&source=1&searchmode=source)
