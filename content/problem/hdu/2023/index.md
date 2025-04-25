---
title: 【HDU】[2023]求平均成绩
type: post
slug: hdu-2023
categories:
  - hdu
ProblemParams:
    ProblemTitle: "求平均成绩"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "65536/32768 K"
---

## Problem Description

假设一个班有n(n<=50)个学生，每人考m(m<=5)门课，求每个学生的平均成绩和每门课的平均成绩，并输出各科成绩均大于等于平均成绩的学生数量。

## Input

输入数据有多个测试实例，每个测试实例的第一行包括两个整数n和m，分别表示学生数和课程数。然后是n行数据，每行包括m个整数（即：考试分数）。

## Output

对于每个测试实例，输出3行数据，第一行包含n个数据，表示n个学生的平均成绩，结果保留两位小数；第二行包含m个数据，表示m门课的平均成绩，结果保留两位小数；第三行是一个整数，表示该班级中各科成绩均大于等于平均成绩的学生数量。  
每个测试实例后面跟一个空行。

## Sample Input

```
2 2
5 10
10 20

```

## Sample Output

```
7.50 15.00
7.50 15.00
1


```

## Author

lcy

## Source

[C语言程序设计练习（四）](https://acm.hdu.edu.cn//search.php?field=problem&key=C%D3%EF%D1%D4%B3%CC%D0%F2%C9%E8%BC%C6%C1%B7%CF%B0%A3%A8%CB%C4%A3%A9&source=1&searchmode=source)
