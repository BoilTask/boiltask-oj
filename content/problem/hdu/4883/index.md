---
title: 【HDU】[4883]TIANKENG’s restaurant
type: post
slug: hdu-4883
categories:
  - hdu
ProblemParams:
    ProblemTitle: "TIANKENG’s restaurant"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "131072/65536 K"
---

## Problem Description

TIANKENG manages a restaurant after graduating from ZCMU, and tens of thousands of customers come to have meal because of its delicious dishes. Today n groups of customers come to enjoy their meal, and there are Xi persons in the ith group in sum. Assuming that each customer can own only one chair. Now we know the arriving time STi and departure time EDi of each group. Could you help TIANKENG calculate the minimum chairs he needs to prepare so that every customer can take a seat when arriving the restaurant?

## Input

The first line contains a positive integer T(T<=100), standing for T test cases in all.  
  
Each cases has a positive integer n(1<=n<=10000), which means n groups of customer. Then following n lines, each line there is a positive integer Xi(1<=Xi<=100), referring to the sum of the number of the ith group people, and the arriving time STi and departure time Edi(the time format is hh:mm, 0<=hh<24, 0<=mm<60), Given that the arriving time must be earlier than the departure time.  
  
Pay attention that when a group of people arrive at the restaurant as soon as a group of people leaves from the restaurant, then the arriving group can be arranged to take their seats if the seats are enough.

## Output

For each test case, output the minimum number of chair that TIANKENG needs to prepare.

## Sample Input

```
2
2
6 08:00 09:00
5 08:59 09:59
2
6 08:00 09:00
5 09:00 10:00
```

## Sample Output

```
11
6
```

## Source

[BestCoder Round #2](https://acm.hdu.edu.cn//search.php?field=problem&key=BestCoder+Round+%232&source=1&searchmode=source)
