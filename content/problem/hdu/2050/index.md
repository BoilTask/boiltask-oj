---
title: 【HDU】[2050]折线分割平面
type: post
slug: hdu-2050
categories:
  - hdu
ProblemParams:
    ProblemTitle: "折线分割平面"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "65536/32768 K"
---

## Problem Description

我们看到过很多直线分割平面的题目，今天的这个题目稍微有些变化，我们要求的是n条折线分割平面的最大数目。比如，一条折线可以将平面分成两部分，两条折线最多可以将平面分成7部分，具体如下所示。  
![](https://r2-oj.boiltask.com/hdu-2050/bd8931aa6965d72f5f5e60b77b96a122)

## Input

输入数据的第一行是一个整数C,表示测试实例的个数，然后是C 行数据，每行包含一个整数n(0<n<=10000),表示折线的数量。

## Output

对于每个测试实例，请输出平面的最大分割数，每个实例的输出占一行。

## Sample Input

```
2
1
2

```

## Sample Output

```
2
7

```

## Author

lcy

## Source

[递推求解专题练习（For Beginner）](https://acm.hdu.edu.cn//search.php?field=problem&key=%B5%DD%CD%C6%C7%F3%BD%E2%D7%A8%CC%E2%C1%B7%CF%B0%A3%A8For+Beginner%A3%A9&source=1&searchmode=source)
