---
title: 【POJ】[3187]Backward Digit Sums
type: post
slug: poj-3187
categories:
  - poj
ProblemParams:
    ProblemTitle: "Backward Digit Sums"
    TimeLimit: "1000MS"
    MemoryLimit: "65536K"
---

## Description

FJ and his cows enjoy playing a mental game. They write down the numbers from 1 to N (1 <= N <= 10) in a certain order and then sum adjacent numbers to produce a new list with one fewer number. They repeat this until only a single number is left. For example, one instance of the game (when N=4) might go like this:  
  
```
    3   1   2   4

      4   3   6

        7   9

         16
```
Behind FJ's back, the cows have started playing a more difficult game, in which they try to determine the starting sequence from only the final total and the number N. Unfortunately, the game is a bit above FJ's mental arithmetic capabilities.  
  
Write a program to help FJ play the game and keep up with the cows.

## Input

Line 1: Two space-separated integers: N and the final sum.

## Output

Line 1: Two space-separated integers: N and the final sum.

## Sample Input

```
4 16
```

## Sample Output

```
3 1 2 4
```

## Hint

Explanation of the sample:  
  
There are other possible sequences, such as 3 2 1 4, but 3 1 2 4 is the lexicographically smallest.

## Source

[USACO 2006 February Gold & Silver](http://poj.org/searchproblem?field=source&key=USACO+2006+February+Gold+%26+Silver)
