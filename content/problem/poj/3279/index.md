---
title: 【POJ】[3279]Fliptile
type: post
slug: poj-3279
categories:
  - poj
ProblemParams:
    ProblemTitle: "Fliptile"
    TimeLimit: "2000MS"
    MemoryLimit: "65536K"
---

## Description

Farmer John knows that an intellectually satisfied cow is a happy cow who will give more milk. He has arranged a brainy activity for cows in which they manipulate an *M* × *N* grid (1 ≤ *M* ≤ 15; 1 ≤ *N* ≤ 15) of square tiles, each of which is colored black on one side and white on the other side.

As one would guess, when a single white tile is flipped, it changes to black; when a single black tile is flipped, it changes to white. The cows are rewarded when they flip the tiles so that each tile has the white side face up. However, the cows have rather large hooves and when they try to flip a certain tile, they also flip all the adjacent tiles (tiles that share a full edge with the flipped tile). Since the flips are tiring, the cows want to minimize the number of flips they have to make.

Help the cows determine the minimum number of flips required, and the locations to flip to achieve that minimum. If there are multiple ways to achieve the task with the minimum amount of flips, return the one with the least lexicographical ordering in the output when considered as a string. If the task is impossible, print one line with the word "IMPOSSIBLE".

## Input

Line 1: Two space-separated integers: *M* and *N*  
Lines 2..*M*+1: Line *i*+1 describes the colors (left to right) of row i of the grid with *N* space-separated integers which are 1 for black and 0 for white

## Output

Line 1: Two space-separated integers: *M* and *N*  
Lines 2..*M*+1: Line *i*+1 describes the colors (left to right) of row i of the grid with *N* space-separated integers which are 1 for black and 0 for white

## Sample Input

```
4 4
1 0 0 1
0 1 1 0
0 1 1 0
1 0 0 1
```

## Sample Output

```
0 0 0 0
1 0 0 1
1 0 0 1
0 0 0 0
```

## Source

[USACO 2007 Open Silver](http://poj.org/searchproblem?field=source&key=USACO+2007+Open+Silver)
