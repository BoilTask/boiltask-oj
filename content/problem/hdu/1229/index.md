---
title: 【HDU】[1229]还是A+B
type: post
slug: hdu-1229
categories:
  - hdu
ProblemParams:
    ProblemTitle: "还是A+B"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "65536/32768 K"
---

## Problem Description

读入两个小于10000的正整数A和B，计算A+B。需要注意的是：如果A和B的末尾K（不超过8）位数字相同，请直接输出-1。

## Input

测试输入包含若干测试用例，每个测试用例占一行，格式为"A B K"，相邻两数字有一个空格间隔。当A和B同时为0时输入结束，相应的结果不要输出。

## Output

对每个测试用例输出1行，即A+B的值或者是-1。

## Sample Input

```
1 2 1
11 21 1
108 8 2
36 64 3
0 0 1

```

## Sample Output

```
3
-1
-1
100

```

## Source

[浙大计算机研究生复试上机考试-2006年](https://acm.hdu.edu.cn//search.php?field=problem&key=%D5%E3%B4%F3%BC%C6%CB%E3%BB%FA%D1%D0%BE%BF%C9%FA%B8%B4%CA%D4%C9%CF%BB%FA%BF%BC%CA%D4-2006%C4%EA&source=1&searchmode=source)
