---
title: 【HDU】[3635]Dragon Balls
type: post
slug: hdu-3635
categories:
  - hdu
ProblemParams:
    ProblemTitle: "Dragon Balls"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "32768/32768 K"
---

## Problem Description

Five hundred years later, the number of dragon balls will increase unexpectedly, so it's too difficult for Monkey King(WuKong) to gather all of the dragon balls together.  
<div style="text-align: center;"><img style="max-width:100%;" src="https://r2-oj.boiltask.com/hdu-3635/d17839f80bb174d33cdd52db31e43876"></div>  
His country has N cities and there are exactly N dragon balls in the world. At first, for the ith dragon ball, the sacred dragon will puts it in the ith city. Through long years, some cities' dragon ball(s) would be transported to other cities. To save physical strength WuKong plans to take Flying Nimbus Cloud, a magical flying cloud to gather dragon balls.  
Every time WuKong will collect the information of one dragon ball, he will ask you the information of that ball. You must tell him which city the ball is located and how many dragon balls are there in that city, you also need to tell him how many times the ball has been transported so far.

## Input

The first line of the input is a single positive integer T(0 < T <= 100).  
For each case, the first line contains two integers: N and Q (2 < N <= 10000 , 2 < Q <= 10000).  
Each of the following Q lines contains either a fact or a question as the follow format:  
  T A B : All the dragon balls which are in the same city with A have been transported to the city the Bth ball in. You can assume that the two cities are different.  
  Q A : WuKong want to know X (the id of the city Ath ball is in), Y (the count of balls in Xth city) and Z (the tranporting times of the Ath ball). (1 <= A, B <= N)

## Output

For each test case, output the test case number formated as sample output. Then for each query, output a line with three integers X Y Z saparated by a blank space.

## Sample Input

```
2
3 3
T 1 2
T 3 2
Q 2
3 4
T 1 2
Q 1
T 1 3
Q 1
```

## Sample Output

```
Case 1:
2 3 0
Case 2:
2 2 1
3 3 2
```

## Author

possessor WC

## Source

[2010 ACM-ICPC Multi-University Training Contest（19）——Host by HDU](https://acm.hdu.edu.cn//search.php?field=problem&key=2010+ACM-ICPC+Multi-University+Training+Contest%A3%A819%A3%A9%A1%AA%A1%AAHost+by+HDU&source=1&searchmode=source)
