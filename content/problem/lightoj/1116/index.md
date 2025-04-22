---
title: 【LightOJ】[1116]Ekka Dokka
type: post
slug: lightoj-1116
categories:
  - lightoj
ProblemParams:
    ProblemTitle: "Ekka Dokka"
    TimeLimit: "1 seconds"
    MemoryLimit: "64 MB"
---

## Description

Ekka and his friend Dokka decided to buy a cake. They both love cakes and that's why they want to share the cake after buying it. As the name suggested that Ekka is very fond of odd numbers and Dokka is very fond of even numbers, they want to divide the cake such that Ekka gets a share of **N** square centimeters and Dokka gets a share of **M** square centimeters where **N** is odd and **M** is even. Both **N** and **M** are positive integers.

They want to divide the cake such that **N \* M = W**, where **W** is the dashing factor set by them. Now you know their dashing factor, you have to find whether they can buy the desired cake or not.

## Input

Input starts with an integer **T (≤ 10000)**, denoting the number of test cases.

Each case contains an integer **W (2 ≤ W < 263)**. And **W** will not be a power of **2**.

## Output

For each case, print the case number first. After that print `Impossible` if they can't buy their desired cake. If they can buy such a cake, you have to print **N** and **M**. If there are multiple solutions, then print the result where **M** is as small as possible.

## Sample Input

```
3
10
5
12

```

## Sample Output

```
Case 1: 5 2
Case 2: Impossible
Case 3: 3 4

```
