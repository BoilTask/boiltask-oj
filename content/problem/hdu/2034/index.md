---
title: 【HDU】[2034]人见人爱A-B
type: post
slug: hdu-2034
categories:
  - hdu
---

# 人见人爱A-B

## Problem Description

参加过上个月月赛的同学一定还记得其中的一个最简单的题目，就是{A}+{B}，那个题目求的是两个集合的并集，今天我们这个A-B求的是两个集合的差，就是做集合的减法运算。（当然，大家都知道集合的定义，就是同一个集合中不会有两个相同的元素，这里还是提醒大家一下）  
  
呵呵，很简单吧？

## Input

每组输入数据占1行,每行数据的开始是2个整数n(0<=n<=100)和m(0<=m<=100),分别表示集合A和集合B的元素个数，然后紧跟着n+m个元素，前面n个元素属于集合A，其余的属于集合B. 每个元素为不超出int范围的整数,元素之间有一个空格隔开.  
如果n=0并且m=0表示输入的结束，不做处理。

## Output

针对每组数据输出一行数据,表示A-B的结果,如果结果为空集合，则输出“NULL”,否则从小到大输出结果,为了简化问题，每个元素后面跟一个空格.

## Sample Input

```
3 3 1 2 3 1 4 7
3 7 2 5 8 2 3 4 5 6 7 8 
0 0

```

## Sample Output

```
2 3 
NULL

```

## Author

lcy

## Source

[ACM程序设计期末考试（2006/06/07）](https://acm.hdu.edu.cn//search.php?field=problem&key=ACM%B3%CC%D0%F2%C9%E8%BC%C6%C6%DA%C4%A9%BF%BC%CA%D4%A3%A82006%2F06%2F07%A3%A9&source=1&searchmode=source)
