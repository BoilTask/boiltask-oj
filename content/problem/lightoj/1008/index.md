---
title: 【LightOJ】[1008]Fibsieve's Fantabulous Birthday
type: post
slug: lightoj-1008
categories:
  - lightoj
ProblemParams:
    ProblemTitle: "Fibsieve's Fantabulous Birthday"
    TimeLimit: "1 seconds"
    MemoryLimit: "64 MB"
---

## Description

Fibsieve had a fantabulous (yes, it's an actual word) birthday party this year. He had so many gifts that he was actually thinking of not having a party next year. Among these gifts there was an **N x N** glass chessboard that had a light in each of its cells. When the board was turned on a distinct cell would light up every second, and then go dark.

The cells would light up in the sequence shown in the diagram. Each cell is marked with the second in which it would light up.

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| 25 | 24 | 23 | 22 | 21 |
| 10 | 11 | 12 | 13 | 20 |
| 9 | 8 | 7 | 14 | 19 |
| 2 | 3 | 6 | 15 | 18 |
| 1 | 4 | 5 | 16 | 17 |

In the first second the light at cell (1, 1) would be on. And in the 5th second the cell (3, 1) would be on. Now, Fibsieve is trying to predict which cell will light up at a certain time (given in seconds). Assume that **N** is large enough.

## Input

Input starts with an integer **T (≤ 200)**, denoting the number of test cases.

Each case will contain an integer **S (1 ≤ S ≤ 1015)** which stands for the time.

## Output

For each case you have to print the case number and two numbers **(x, y)**, the column and the row number.

## Sample Input

```
3
8
20
25

```

## Sample Output

```
Case 1: 2 3
Case 2: 5 4
Case 3: 1 5

```
