---
title: 【POJ】[2387]Til the Cows Come Home
type: post
slug: poj-2387
categories:
  - poj
ProblemParams:
    ProblemTitle: "Til the Cows Come Home"
    TimeLimit: "1000MS"
    MemoryLimit: "65536K"
---

## Description

Bessie is out in the field and wants to get back to the barn to get as much sleep as possible before Farmer John wakes her for the morning milking. Bessie needs her beauty sleep, so she wants to get back as quickly as possible.  
  
Farmer John's field has N (2 <= N <= 1000) landmarks in it, uniquely numbered 1..N. Landmark 1 is the barn; the apple tree grove in which Bessie stands all day is landmark N. Cows travel in the field using T (1 <= T <= 2000) bidirectional cow-trails of various lengths between the landmarks. Bessie is not confident of her navigation ability, so she always stays on a trail from its start to its end once she starts it.  
  
Given the trails between the landmarks, determine the minimum distance Bessie must walk to get back to the barn. It is guaranteed that some such route exists.

## Input

\* Line 1: Two integers: T and N  
  
\* Lines 2..T+1: Each line describes a trail as three space-separated integers. The first two integers are the landmarks between which the trail travels. The third integer is the length of the trail, range 1..100.

## Output

\* Line 1: Two integers: T and N  
  
\* Lines 2..T+1: Each line describes a trail as three space-separated integers. The first two integers are the landmarks between which the trail travels. The third integer is the length of the trail, range 1..100.

## Sample Input

```
5 5
1 2 20
2 3 30
3 4 20
4 5 20
1 5 100
```

## Sample Output

```
90
```

## Hint

INPUT DETAILS:  
  
There are five landmarks.  
  
OUTPUT DETAILS:  
  
Bessie can get home by following trails 4, 3, 2, and 1.

## Source

[USACO 2004 November](http://poj.org/searchproblem?field=source&key=USACO+2004+November)
