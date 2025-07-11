---
title: 【HDU】[1010]Tempter of the Bone
type: post
slug: hdu-1010
categories:
  - hdu
ProblemParams:
    ProblemTitle: "Tempter of the Bone"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "65536/32768 K"
---

## Problem Description

The doggie found a bone in an ancient maze, which fascinated him a lot. However, when he picked it up, the maze began to shake, and the doggie could feel the ground sinking. He realized that the bone was a trap, and he tried desperately to get out of this maze.  
  
The maze was a rectangle with sizes N by M. There was a door in the maze. At the beginning, the door was closed and it would open at the T-th second for a short period of time (less than 1 second). Therefore the doggie had to arrive at the door on exactly the T-th second. In every second, he could move one block to one of the upper, lower, left and right neighboring blocks. Once he entered a block, the ground of this block would start to sink and disappear in the next second. He could not stay at one block for more than one second, nor could he move into a visited block. Can the poor doggie survive? Please help him.

## Input

The input consists of multiple test cases. The first line of each test case contains three integers N, M, and T (1 < N, M < 7; 0 < T < 50), which denote the sizes of the maze and the time at which the door will open, respectively. The next N lines give the maze layout, with each line containing M characters. A character is one of the following:  
  
'X': a block of wall, which the doggie cannot enter;  
'S': the start point of the doggie;  
'D': the Door; or  
'.': an empty block.  
  
The input is terminated with three 0's. This test case is not to be processed.

## Output

For each test case, print in one line "YES" if the doggie can survive, or "NO" otherwise.

## Sample Input

```
4 4 5
S.X.
..X.
..XD
....
3 4 5
S.X.
..X.
...D
0 0 0

```

## Sample Output

```
NO
YES

```

## Author

ZHANG, Zheng

## Source

[ZJCPC2004](https://acm.hdu.edu.cn//search.php?field=problem&key=ZJCPC2004&source=1&searchmode=source)
