---
title: 【HDU】[2092]整数解
type: post
slug: hdu-2092
categories:
  - hdu
---

# 整数解

## Problem Description

有二个整数，它们加起来等于某个整数，乘起来又等于另一个整数，它们到底是真还是假，也就是这种整数到底存不存在，实在有点吃不准，你能快速回答吗？看来只能通过编程。  
例如：  
x + y = 9，x \* y = 15 ? 找不到这样的整数x和y  
1+4=5，1\*4=4，所以，加起来等于5，乘起来等于4的二个整数为1和4  
7+(-8)=-1，7\*（-8）=-56，所以，加起来等于-1，乘起来等于-56的二个整数为7和-8

## Input

输入数据为成对出现的整数n，m（-10000<n,m<10000），它们分别表示整数的和与积，如果两者都为0，则输入结束。

## Output

只需要对于每个n和m，输出“Yes”或者“No”，明确有还是没有这种整数就行了。

## Sample Input

```
9 15
5 4
1 -56
0 0

```

## Sample Output

```
No
Yes
Yes

```

## Author

qianneng

## Source

[迎接新学期——超级Easy版热身赛](https://acm.hdu.edu.cn//search.php?field=problem&key=%D3%AD%BD%D3%D0%C2%D1%A7%C6%DA%A1%AA%A1%AA%B3%AC%BC%B6Easy%B0%E6%C8%C8%C9%ED%C8%FC&source=1&searchmode=source)
