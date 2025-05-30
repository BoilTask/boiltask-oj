---
title: 【HDU】[1859]最小长方形
type: post
slug: hdu-1859
categories:
  - hdu
ProblemParams:
    ProblemTitle: "最小长方形"
    TimeLimit: "1000/1000 MS"
    MemoryLimit: "32768/32768 K"
---

## Problem Description

给定一系列2维平面点的坐标(x, y)，其中x和y均为整数，要求用一个最小的长方形框将所有点框在内。长方形框的边分别平行于x和y坐标轴，点落在边上也算是被框在内。

## Input

测试输入包含若干测试用例，每个测试用例由一系列坐标组成，每对坐标占一行，其中|x|和|y|小于 231；一对0 坐标标志着一个测试用例的结束。注意(0, 0)不作为任何一个测试用例里面的点。一个没有点的测试用例标志着整个输入的结束。

## Output

对每个测试用例，在1行内输出2对整数，其间用一个空格隔开。第1对整数是长方形框左下角的坐标，第2对整数是长方形框右上角的坐标。

## Sample Input

```
12 56
23 56
13 10
0 0
12 34
0 0
0 0

```

## Sample Output

```
12 10 23 56
12 34 12 34

```

## Source

[浙大计算机研究生复试上机考试-2007年](https://acm.hdu.edu.cn//search.php?field=problem&key=%D5%E3%B4%F3%BC%C6%CB%E3%BB%FA%D1%D0%BE%BF%C9%FA%B8%B4%CA%D4%C9%CF%BB%FA%BF%BC%CA%D4-2007%C4%EA&source=1&searchmode=source)
