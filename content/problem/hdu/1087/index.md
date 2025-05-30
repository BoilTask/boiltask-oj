---
title: 【HDU】[1087]Super Jumping! Jumping! Jumping!
type: post
slug: hdu-1087
categories:
  - hdu
ProblemParams:
    ProblemTitle: "Super Jumping! Jumping! Jumping!"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "65536/32768 K"
---

## Problem Description

Nowadays, a kind of chess game called “Super Jumping! Jumping! Jumping!” is very popular in HDU. Maybe you are a good boy, and know little about this game, so I introduce it to you now.  
  
<div style="text-align: center;"><img style="max-width:100%;" src="https://r2-oj.boiltask.com/hdu-1087/3e85fb18af8464c57aa3af38ef4da0bf"></div>  
  
The game can be played by two or more than two players. It consists of a chessboard（棋盘）and some chessmen（棋子）, and all chessmen are marked by a positive integer or “start” or “end”. The player starts from start-point and must jumps into end-point finally. In the course of jumping, the player will visit the chessmen in the path, but everyone must jumps from one chessman to another absolutely bigger (you can assume start-point is a minimum and end-point is a maximum.). And all players cannot go backwards. One jumping can go from a chessman to next, also can go across many chessmen, and even you can straightly get to end-point from start-point. Of course you get zero point in this situation. A player is a winner if and only if he can get a bigger score according to his jumping solution. Note that your score comes from the sum of value on the chessmen in you jumping path.  
Your task is to output the maximum value according to the given chessmen list.

## Input

Input contains multiple test cases. Each test case is described in a line as follow:  
N value\_1 value\_2 …value\_N  
It is guarantied that N is not more than 1000 and all value\_i are in the range of 32-int.  
A test case starting with 0 terminates the input and this test case is not to be processed.

## Output

For each case, print the maximum according to rules, and one line one case.

## Sample Input

```
3 1 3 2
4 1 2 3 4
4 3 3 2 1
0

```

## Sample Output

```
4
10
3

```

## Author

lcy
