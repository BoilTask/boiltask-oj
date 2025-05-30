---
title: 【HDU】[1896]Stones
type: post
slug: hdu-1896
categories:
  - hdu
ProblemParams:
    ProblemTitle: "Stones"
    TimeLimit: "5000/3000 MS"
    MemoryLimit: "65535/32768 K"
---

## Problem Description

Because of the wrong status of the bicycle, Sempr begin to walk east to west every morning and walk back every evening. Walking may cause a little tired, so Sempr always play some games this time.  
There are many stones on the road, when he meet a stone, he will throw it ahead as far as possible if it is the odd stone he meet, or leave it where it was if it is the even stone. Now give you some informations about the stones on the road, you are to tell me the distance from the start point to the farthest stone after Sempr walk by. Please pay attention that if two or more stones stay at the same position, you will meet the larger one(the one with the smallest Di, as described in the Input) first.

## Input

In the first line, there is an Integer T(1<=T<=10), which means the test cases in the input file. Then followed by T test cases.  
For each test case, I will give you an Integer N(0<N<=100,000) in the first line, which means the number of stones on the road. Then followed by N lines and there are two integers Pi(0<=Pi<=100,000) and Di(0<=Di<=1,000) in the line, which means the position of the i-th stone and how far Sempr can throw it.

## Output

Just output one line for one test case, as described in the Description.

## Sample Input

```
2
2
1 5
2 4
2
1 5
6 6

```

## Sample Output

```
11
12

```

## Author

Sempr|CrazyBird|hust07p43

## Source

[HDU 2008-4 Programming Contest](https://acm.hdu.edu.cn//search.php?field=problem&key=HDU+2008-4+Programming+Contest&source=1&searchmode=source)
