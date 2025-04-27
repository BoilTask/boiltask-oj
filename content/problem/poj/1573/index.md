---
title: 【POJ】[1573]Robot Motion
type: post
slug: poj-1573
categories:
  - poj
ProblemParams:
    ProblemTitle: "Robot Motion"
    TimeLimit: "1000MS"
    MemoryLimit: "10000K"
---

## Description

<div style="text-align: center;"><img src="https://r2-oj.boiltask.com/poj-1573/ae519adb33b823f9a2936a60d4fa3a66"></div>  
A robot has been programmed to follow the instructions in its path. Instructions for the next direction the robot is to move are laid down in a grid. The possible instructions are  
  
N north (up the page)  
S south (down the page)  
E east (to the right on the page)  
W west (to the left on the page)  
  
For example, suppose the robot starts on the north (top) side of Grid 1 and starts south (down). The path the robot follows is shown. The robot goes through 10 instructions in the grid before leaving the grid.  
  
Compare what happens in Grid 2: the robot goes through 3 instructions only once, and then starts a loop through 8 instructions, and never exits.  
  
You are to write a program that determines how long it takes a robot to get out of the grid or how the robot loops around.

## Input

There will be one or more grids for robots to navigate. The data for each is in the following form. On the first line are three integers separated by blanks: the number of rows in the grid, the number of columns in the grid, and the number of the column in which the robot enters from the north. The possible entry columns are numbered starting with one at the left. Then come the rows of the direction instructions. Each grid will have at least one and at most 10 rows and columns of instructions. The lines of instructions contain only the characters N, S, E, or W with no blanks. The end of input is indicated by a row containing 0 0 0.

## Output

There will be one or more grids for robots to navigate. The data for each is in the following form. On the first line are three integers separated by blanks: the number of rows in the grid, the number of columns in the grid, and the number of the column in which the robot enters from the north. The possible entry columns are numbered starting with one at the left. Then come the rows of the direction instructions. Each grid will have at least one and at most 10 rows and columns of instructions. The lines of instructions contain only the characters N, S, E, or W with no blanks. The end of input is indicated by a row containing 0 0 0.

## Sample Input

```
3 6 5
NEESWE
WWWESS
SNWWWW
4 5 1
SESWE
EESNW
NWEEN
EWSEN
0 0 0
```

## Sample Output

```
10 step(s) to exit
3 step(s) before a loop of 8 step(s)

```

## Source

[Mid-Central USA 1999](http://poj.org/searchproblem?field=source&key=Mid-Central+USA+1999)
