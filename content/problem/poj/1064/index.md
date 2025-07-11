---
title: 【POJ】[1064]Cable master
type: post
slug: poj-1064
categories:
  - poj
ProblemParams:
    ProblemTitle: "Cable master"
    TimeLimit: "1000MS"
    MemoryLimit: "10000K"
---

## Description

Inhabitants of the Wonderland have decided to hold a regional programming contest. The Judging Committee has volunteered and has promised to organize the most honest contest ever. It was decided to connect computers for the contestants using a "star" topology - i.e. connect them all to a single central hub. To organize a truly honest contest, the Head of the Judging Committee has decreed to place all contestants evenly around the hub on an equal distance from it.  
To buy network cables, the Judging Committee has contacted a local network solutions provider with a request to sell for them a specified number of cables with equal lengths. The Judging Committee wants the cables to be as long as possible to sit contestants as far from each other as possible.  
The Cable Master of the company was assigned to the task. He knows the length of each cable in the stock up to a centimeter,and he can cut them with a centimeter precision being told the length of the pieces he must cut. However, this time, the length is not known and the Cable Master is completely puzzled.  
You are to help the Cable Master, by writing a program that will determine the maximal possible length of a cable piece that can be cut from the cables in the stock, to get the specified number of pieces.

## Input

The first line of the input file contains two integer numb ers N and K, separated by a space. N (1 = N = 10000) is the number of cables in the stock, and K (1 = K = 10000) is the number of requested pieces. The first line is followed by N lines with one number per line, that specify the length of each cable in the stock in meters. All cables are at least 1 meter and at most 100 kilometers in length. All lengths in the input file are written with a centimeter precision, with exactly two digits after a decimal point.

## Output

The first line of the input file contains two integer numb ers N and K, separated by a space. N (1 = N = 10000) is the number of cables in the stock, and K (1 = K = 10000) is the number of requested pieces. The first line is followed by N lines with one number per line, that specify the length of each cable in the stock in meters. All cables are at least 1 meter and at most 100 kilometers in length. All lengths in the input file are written with a centimeter precision, with exactly two digits after a decimal point.

## Sample Input

```
4 11
8.02
7.43
4.57
5.39
```

## Sample Output

```
2.00
```

## Source

[Northeastern Europe 2001](http://poj.org/searchproblem?field=source&key=Northeastern+Europe+2001)
