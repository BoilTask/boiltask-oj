---
title: 【HDU】[1233]还是畅通工程
type: post
slug: hdu-1233
categories:
  - hdu
ProblemParams:
    ProblemTitle: "还是畅通工程"
    TimeLimit: "4000/2000 MS"
    MemoryLimit: "65536/32768 K"
---

## Problem Description

某省调查乡村交通状况，得到的统计表中列出了任意两村庄间的距离。省政府“畅通工程”的目标是使全省任何两个村庄间都可以实现公路交通（但不一定有直接的公路相连，只要能间接通过公路可达即可），并要求铺设的公路总长度为最小。请计算最小的公路总长度。

## Input

测试输入包含若干测试用例。每个测试用例的第1行给出村庄数目N ( < 100 )；随后的N(N-1)/2行对应村庄间的距离，每行给出一对正整数，分别是两个村庄的编号，以及此两村庄间的距离。为简单起见，村庄从1到N编号。  
当N为0时，输入结束，该用例不被处理。

## Output

对每个测试用例，在1行里输出最小的公路总长度。

## Sample Input

```
3
1 2 1
1 3 2
2 3 4
4
1 2 1
1 3 4
1 4 1
2 3 3
2 4 2
3 4 5
0

```

## Sample Output

```
3
5
Huge input, scanf is recommended.

```

## Hint

Hint

## Source

[浙大计算机研究生复试上机考试-2006年](https://acm.hdu.edu.cn//search.php?field=problem&key=%D5%E3%B4%F3%BC%C6%CB%E3%BB%FA%D1%D0%BE%BF%C9%FA%B8%B4%CA%D4%C9%CF%BB%FA%BF%BC%CA%D4-2006%C4%EA&source=1&searchmode=source)
