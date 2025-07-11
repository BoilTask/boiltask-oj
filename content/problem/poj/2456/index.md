---
title: 【POJ】[2456]Aggressive cows
type: post
slug: poj-2456
categories:
  - poj
ProblemParams:
    ProblemTitle: "Aggressive cows"
    TimeLimit: "1000MS"
    MemoryLimit: "65536K"
---

## Description

Farmer John has built a new long barn, with N (2 <= N <= 100,000) stalls. The stalls are located along a straight line at positions x1,...,xN (0 <= xi <= 1,000,000,000).  
  
His C (2 <= C <= N) cows don't like this barn layout and become aggressive towards each other once put into a stall. To prevent the cows from hurting each other, FJ want to assign the cows to the stalls, such that the minimum distance between any two of them is as large as possible. What is the largest minimum distance?

## Input

\* Line 1: Two space-separated integers: N and C  
  
\* Lines 2..N+1: Line i+1 contains an integer stall location, xi

## Output

\* Line 1: Two space-separated integers: N and C  
  
\* Lines 2..N+1: Line i+1 contains an integer stall location, xi

## Sample Input

```
5 3
1
2
8
4
9
```

## Sample Output

```
3
```

## Hint

OUTPUT DETAILS:  
  
FJ can put his 3 cows in the stalls at positions 1, 4 and 8, resulting in a minimum distance of 3.  
  
Huge input data,scanf is recommended.

## Source

[USACO 2005 February Gold](http://poj.org/searchproblem?field=source&key=USACO+2005+February+Gold)
