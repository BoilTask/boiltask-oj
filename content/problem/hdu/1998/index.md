---
title: 【HDU】[1998]奇数阶魔方
type: post
slug: hdu-1998
categories:
  - hdu
ProblemParams:
    ProblemTitle: "奇数阶魔方"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "65536/32768 K"
---

## Problem Description

一个 n 阶方阵的元素是1,2,...,n^2,它的每行，每列和2条对角线上元素的和相等，这样  
的方阵叫魔方。n为奇数时我们有1种构造方法，叫做“右上方” ，例如下面给出n=3，5，7时  
的魔方.  
3  
8 1 6  
3 5 7  
4 9 2  
5  
17 24 1 8 15  
23 5 7 14 16  
4 6 13 20 22  
10 12 19 21 3  
11 18 25 2 9  
7  
30 39 48 1 10 19 28  
38 47 7 9 18 27 29  
46 6 8 17 26 35 37  
5 14 16 25 34 36 45  
13 15 24 33 42 44 4  
21 23 32 41 43 3 12  
22 31 40 49 2 11 20  
第1行中间的数总是1，最后1行中间的数是n^2,他的右边是2，从这三个魔方，你可看出“右  
上方”是何意。

## Input

包含多组数据，首先输入T,表示有T组数据.每组数据1行给出n(3<=n<=19)是奇数。

## Output

对于每组数据，输出n阶魔方，每个数占4格，右对齐

## Sample Input

```
2
3
5

```

## Sample Output

```
   8   1   6
   3   5   7
   4   9   2
  17  24   1   8  15
  23   5   7  14  16
   4   6  13  20  22
  10  12  19  21   3
  11  18  25   2   9

```

## Author

Zhousc@ECJTU

## Source

[ECJTU 2008 Spring Contest](https://acm.hdu.edu.cn//search.php?field=problem&key=ECJTU+2008+Spring+Contest&source=1&searchmode=source)
