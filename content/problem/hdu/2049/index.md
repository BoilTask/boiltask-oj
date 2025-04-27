---
title: 【HDU】[2049]不容易系列之(4)——考新郎
type: post
slug: hdu-2049
categories:
  - hdu
ProblemParams:
    ProblemTitle: "不容易系列之(4)——考新郎"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "65536/32768 K"
---

## Problem Description

国庆期间,省城HZ刚刚举行了一场盛大的集体婚礼,为了使婚礼进行的丰富一些,司仪临时想出了有一个有意思的节目,叫做"考新郎",具体的操作是这样的:  
![](https://r2-oj.boiltask.com/hdu-2049/33e86028b0d46c74f918d49798470480)  
  
首先,给每位新娘打扮得几乎一模一样,并盖上大大的红盖头随机坐成一排;  
然后,让各位新郎寻找自己的新娘.每人只准找一个,并且不允许多人找一个.  
最后,揭开盖头,如果找错了对象就要当众跪搓衣板...  
  
看来做新郎也不是容易的事情...  
  
假设一共有N对新婚夫妇,其中有M个新郎找错了新娘,求发生这种情况一共有多少种可能.

## Input

输入数据的第一行是一个整数C,表示测试实例的个数，然后是C行数据，每行包含两个整数N和M(1<M<=N<=20)。

## Output

对于每个测试实例，请输出一共有多少种发生这种情况的可能，每个实例的输出占一行。

## Sample Input

```
2
2 2
3 2

```

## Sample Output

```
1
3

```

## Author

lcy

## Source

[递推求解专题练习（For Beginner）](https://acm.hdu.edu.cn//search.php?field=problem&key=%B5%DD%CD%C6%C7%F3%BD%E2%D7%A8%CC%E2%C1%B7%CF%B0%A3%A8For+Beginner%A3%A9&source=1&searchmode=source)
