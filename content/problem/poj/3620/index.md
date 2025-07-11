---
title: 【POJ】[3620]Avoid The Lakes
type: post
slug: poj-3620
categories:
  - poj
ProblemParams:
    ProblemTitle: "Avoid The Lakes"
    TimeLimit: "1000MS"
    MemoryLimit: "65536K"
---

## Description

Farmer John's farm was flooded in the most recent storm, a fact only aggravated by the information that his cows are deathly afraid of water. His insurance agency will only repay him, however, an amount depending on the size of the largest "lake" on his farm.  
  
The farm is represented as a rectangular grid with *N* (1 ≤ *N* ≤ 100) rows and *M* (1 ≤ *M* ≤ 100) columns. Each cell in the grid is either dry or submerged, and exactly *K* (1 ≤ *K* ≤ *N* × *M*) of the cells are submerged. As one would expect, a lake has a central cell to which other cells connect by sharing a long edge (not a corner). Any cell that shares a long edge with the central cell or shares a long edge with any connected cell becomes a connected cell and is part of the lake.

## Input

\* Line 1: Three space-separated integers: *N*, *M*, and *K*  
\* Lines 2..*K*+1: Line *i*+1 describes one submerged location with two space separated integers that are its row and column: *R* and *C*

## Output

\* Line 1: Three space-separated integers: *N*, *M*, and *K*  
\* Lines 2..*K*+1: Line *i*+1 describes one submerged location with two space separated integers that are its row and column: *R* and *C*

## Sample Input

```
3 4 5
3 2
2 2
3 1
2 3
1 1
```

## Sample Output

```
4
```

## Source

[USACO 2007 November Bronze](http://poj.org/searchproblem?field=source&key=USACO+2007+November+Bronze)
