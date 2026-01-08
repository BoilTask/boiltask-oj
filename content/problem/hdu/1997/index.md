---
title: 【HDU】[1997]汉诺塔VII
type: post
slug: hdu-1997
categories:
  - hdu
ProblemParams:
    ProblemTitle: "汉诺塔VII"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "65536/32768 K"
---

## Problem Description

n个盘子的汉诺塔问题的最少移动次数是2^n-1,即在移动过程中会产生2^n个系列。由于发生错移产生的系列就增加了，这种错误是放错了柱子，并不会把大盘放到小盘上，即各柱子从下往上的大小仍保持如下关系 ：  
n=m+p+q  
a1>a2>...>am  
b1>b2>...>bp  
c1>c2>...>cq  
ai是A柱上的盘的盘号系列，bi是B柱上的盘的盘号系列， ci是C柱上的盘的盘号系列，最初目标是将A柱上的n个盘子移到C盘. 给出1个系列，判断它是否是在正确的移动中产生的系列.  
例1：n=3  
3  
2  
1  
是正确的  
例2：n=3  
3  
1  
2  
是不正确的。  
注：对于例2如果目标是将A柱上的n个盘子移到B盘. 则是正确的.

## Input

包含多组数据，首先输入T,表示有T组数据.每组数据4行，第1行N是盘子的数目N<=64.  
后3行如下  
m a1 a2 ...am  
p b1 b2 ...bp  
q c1 c2 ...cq  
N=m+p+q,0<=m<=N,0<=p<=N,0<=q<=N,

## Output

对于每组数据，判断它是否是在正确的移动中产生的系列.正确输出true，否则false

## Sample Input

```
6
3
1 3
1 2
1 1
3
1 3
1 1
1 2
6
3 6 5 4
1 1
2 3 2
6
3 6 5 4
2 3 2
1 1
3
1 3
1 2
1 1
20
2 20 17
2 19 18
16 16 15 14 13 12 11 10 9 8 7 6 5 4 3 2 1

```

## Sample Output

```
true
false
false
false
true
true

```

## Author

Zhousc@ECJTU

## Source

[ECJTU 2008 Spring Contest](https://acm.hdu.edu.cn//search.php?field=problem&key=ECJTU+2008+Spring+Contest&source=1&searchmode=source)
