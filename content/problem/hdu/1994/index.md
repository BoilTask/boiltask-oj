---
title: 【HDU】[1994]利息计算
type: post
slug: hdu-1994
categories:
  - hdu
ProblemParams:
    ProblemTitle: "利息计算"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "65536/32768 K"
---

## Problem Description

为自行解决学费，chx勤工俭学收入10000元以1年定期存入银行，年利率为3.7% 。利率  
按年计算，表示100元存1年的利息为3.7元.实际上有时提前有时推迟取，因此实际利息按天  
计算，1年按365天计算，因此Q天的利息是  
本金\*3.7/100 \*Q/365  
存了100天后1年定期年利息提高到3.9%。如将存款提前全取出，再存1年定期。那么前面的  
100天只能按活期利息1.7%计算。  
100天的利息和本金：10000（1+1.7/100\*100/365)=10046.6  
再存1年定期 ：10046.6(1+3.9/100)=10438.4  
得到的利息加本金为10438.4  
如果无视利息的提高，再存1年。得到的利息加本金为（定期推迟取，利率不变）  
10000（1+3.7/100\*（100+365）/365)=10471.4

## Input

输入数据有多组，第1行为整数T,是数据的组数.每组占一行5个数，Y-存入的本金<=100000,  
Q-已存天数<=365,e-活期利率,f-定期利率,g-提高后的定期利率.

## Output

每组数据输出2行.  
第1行,提前支取后再存1年所得本金和利息.  
第2行,继续存1年,Q+365天后所得本金和利息.

## Sample Input

```
4 
10000 100 2.3 3.7 3.9
10000 100 1.7 3.7 3.9 
10000 200 1.7 3.7 3.9 
10000 300 1.7 3.7 3.9 

```

## Sample Output

```
10455.5
10471.4
10438.4
10471.4
10486.8
10572.7
10535.2
10674.1

```

## Author

Zhousc@ECJTU

## Source

[ECJTU 2008 Spring Contest](https://acm.hdu.edu.cn//search.php?field=problem&key=ECJTU+2008+Spring+Contest&source=1&searchmode=source)
