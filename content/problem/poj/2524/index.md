---
title: 【POJ】[2524]Ubiquitous Religions
type: post
slug: poj-2524
categories:
  - poj
ProblemParams:
    ProblemTitle: "Ubiquitous Religions"
    TimeLimit: "5000MS"
    MemoryLimit: "65536K"
---

## Description

There are so many different religions in the world today that it is difficult to keep track of them all. You are interested in finding out how many different religions students in your university believe in.  
  
You know that there are n students in your university (0 < n <= 50000). It is infeasible for you to ask every student their religious beliefs. Furthermore, many students are not comfortable expressing their beliefs. One way to avoid these problems is to ask m (0 <= m <= n(n-1)/2) pairs of students and ask them whether they believe in the same religion (e.g. they may know if they both attend the same church). From this data, you may not know what each person believes in, but you can get an idea of the upper bound of how many different religions can be possibly represented on campus. You may assume that each student subscribes to at most one religion.

## Input

The input consists of a number of cases. Each case starts with a line specifying the integers n and m. The next m lines each consists of two integers i and j, specifying that students i and j believe in the same religion. The students are numbered 1 to n. The end of input is specified by a line in which n = m = 0.

## Output

The input consists of a number of cases. Each case starts with a line specifying the integers n and m. The next m lines each consists of two integers i and j, specifying that students i and j believe in the same religion. The students are numbered 1 to n. The end of input is specified by a line in which n = m = 0.

## Sample Input

```
10 9
1 2
1 3
1 4
1 5
1 6
1 7
1 8
1 9
1 10
10 4
2 3
4 5
4 8
5 8
0 0

```

## Sample Output

```
Case 1: 1
Case 2: 7

```

## Hint

Huge input, scanf is recommended.

## Source

[Alberta Collegiate Programming Contest 2003.10.18](https://web.archive.org/web/20240909023955/http://poj.org/searchproblem?field=source&key=Alberta+Collegiate+Programming+Contest+2003.10.18)
