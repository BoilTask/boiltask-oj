---
title: 【HDU】[5256]序列变换
type: post
slug: hdu-5256
categories:
  - hdu
ProblemParams:
    ProblemTitle: "序列变换"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "32768/32768 K"
---

## Problem Description

我们有一个数列A1,A2...An，你现在要求修改数量最少的元素，使得这个数列严格递增。其中无论是修改前还是修改后，每个元素都必须是整数。  
请输出最少需要修改多少个元素。

## Input

第一行输入一个$T (1 \\leq T \\leq 10)$，表示有多少组数据  
  
每一组数据：  
  
第一行输入一个$N (1 \\leq N \\leq 10^5)$，表示数列的长度  
  
第二行输入N个数$A\_1, A\_2, ..., A\_n$。  
  
每一个数列中的元素都是正整数而且不超过$10^6$。

## Output

对于每组数据，先输出一行  
  
Case #i:  
  
然后输出最少需要修改多少个元素。

## Sample Input

```
2
2
1 10
3
2 5 4
```

## Sample Output

```
Case #1:
0
Case #2:
1
```

## Source

[2015年百度之星程序设计大赛 - 初赛(2)](https://acm.hdu.edu.cn//search.php?field=problem&key=2015%C4%EA%B0%D9%B6%C8%D6%AE%D0%C7%B3%CC%D0%F2%C9%E8%BC%C6%B4%F3%C8%FC+-+%B3%F5%C8%FC%282%29&source=1&searchmode=source)
