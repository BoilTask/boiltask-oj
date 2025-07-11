---
title: 【POJ】[2251]Dungeon Master
type: post
slug: poj-2251
categories:
  - poj
ProblemParams:
    ProblemTitle: "Dungeon Master"
    TimeLimit: "1000MS"
    MemoryLimit: "65536K"
---

## Description

You are trapped in a 3D dungeon and need to find the quickest way out! The dungeon is composed of unit cubes which may or may not be filled with rock. It takes one minute to move one unit north, south, east, west, up or down. You cannot move diagonally and the maze is surrounded by solid rock on all sides.  
  
Is an escape possible? If yes, how long will it take?

## Input

The input consists of a number of dungeons. Each dungeon description starts with a line containing three integers L, R and C (all limited to 30 in size).  
L is the number of levels making up the dungeon.  
R and C are the number of rows and columns making up the plan of each level.  
Then there will follow L blocks of R lines each containing C characters. Each character describes one cell of the dungeon. A cell full of rock is indicated by a '#' and empty cells are represented by a '.'. Your starting position is indicated by 'S' and the exit by the letter 'E'. There's a single blank line after each level. Input is terminated by three zeroes for L, R and C.

## Output

The input consists of a number of dungeons. Each dungeon description starts with a line containing three integers L, R and C (all limited to 30 in size).  
L is the number of levels making up the dungeon.  
R and C are the number of rows and columns making up the plan of each level.  
Then there will follow L blocks of R lines each containing C characters. Each character describes one cell of the dungeon. A cell full of rock is indicated by a '#' and empty cells are represented by a '.'. Your starting position is indicated by 'S' and the exit by the letter 'E'. There's a single blank line after each level. Input is terminated by three zeroes for L, R and C.

## Sample Input

```
3 4 5
S....
.###.
.##..
###.#

#####
#####
##.##
##...

#####
#####
#.###
####E

1 3 3
S##
#E#
###

0 0 0

```

## Sample Output

```
Escaped in 11 minute(s).
Trapped!

```

## Source

[Ulm Local 1997](http://poj.org/searchproblem?field=source&key=Ulm+Local+1997)
