---
title: 【HDU】[2141]Can you find it?
type: post
slug: hdu-2141
categories:
  - hdu
ProblemParams:
    ProblemTitle: "Can you find it?"
    TimeLimit: "10000/3000 MS"
    MemoryLimit: "32768/10000 K"
---

## Problem Description

Give you three sequences of numbers A, B, C, then we give you a number X. Now you need to calculate if you can find the three numbers Ai, Bj, Ck, which satisfy the formula Ai+Bj+Ck = X.

## Input

There are many cases. Every data case is described as followed: In the first line there are three integers L, N, M, in the second line there are L integers represent the sequence A, in the third line there are N integers represent the sequences B, in the forth line there are M integers represent the sequence C. In the fifth line there is an integer S represents there are S integers X to be calculated. 1<=L, N, M<=500, 1<=S<=1000. all the integers are 32-integers.

## Output

For each case, firstly you have to print the case number as the form "Case d:", then for the S queries, you calculate if the formula can be satisfied or not. If satisfied, you print "YES", otherwise print "NO".

## Sample Input

```
3 3 3
1 2 3
1 2 3
1 2 3
3
1
4
10

```

## Sample Output

```
Case 1:
NO
YES
NO

```

## Author

wangye

## Source

[HDU 2007-11 Programming Contest](https://acm.hdu.edu.cn//search.php?field=problem&key=HDU+2007-11++Programming+Contest&source=1&searchmode=source)
