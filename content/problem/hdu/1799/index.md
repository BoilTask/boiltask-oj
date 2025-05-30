---
title: 【HDU】[1799]循环多少次？
type: post
slug: hdu-1799
categories:
  - hdu
ProblemParams:
    ProblemTitle: "循环多少次？"
    TimeLimit: "3000/1000 MS"
    MemoryLimit: "65536/32768 K"
---

## Problem Description

  我们知道，在编程中，我们时常需要考虑到时间复杂度，特别是对于循环的部分。例如，  
如果代码中出现  
for(i=1;i<=n;i++) OP ;  
那么做了n次OP运算，如果代码中出现  
fori=1;i<=n; i++)  
  for(j=i+1;j<=n; j++) OP;  
那么做了n\*(n-1)/2 次OP 操作。  
现在给你已知有m层for循环操作，且每次for中变量的起始值是上一个变量的起始值＋1（第一个变量的起始值是1），终止值都是一个输入的n，问最后OP有总共多少计算量。

## Input

  有T组case，T<=10000。每个case有两个整数m和n，0<m<=2000，0<n<=2000.

## Output

  对于每个case，输出一个值，表示总的计算量，也许这个数字很大，那么你只需要输出除1007留下的余数即可。

## Sample Input

```
2
1 3
2 3

```

## Sample Output

```
3
3

```

## Author

wangye

## Source

[2008 “Insigma International Cup” Zhejiang Collegiate Programming Contest - Warm Up（4）](https://acm.hdu.edu.cn//search.php?field=problem&key=2008+%A1%B0Insigma+International+Cup%A1%B1+Zhejiang+Collegiate+Programming+Contest+-+Warm+Up%A3%A84%A3%A9&source=1&searchmode=source)
