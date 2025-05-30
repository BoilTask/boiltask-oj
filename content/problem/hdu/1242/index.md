---
title: 【HDU】[1242]Rescue
type: post
slug: hdu-1242
categories:
  - hdu
ProblemParams:
    ProblemTitle: "Rescue"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "65536/32768 K"
---

## Problem Description

Angel was caught by the MOLIGPY! He was put in prison by Moligpy. The prison is described as a N \* M (N, M <= 200) matrix. There are WALLs, ROADs, and GUARDs in the prison.  
  
Angel's friends want to save Angel. Their task is: approach Angel. We assume that "approach Angel" is to get to the position where Angel stays. When there's a guard in the grid, we must kill him (or her?) to move into the grid. We assume that we moving up, down, right, left takes us 1 unit time, and killing a guard takes 1 unit time, too. And we are strong enough to kill all the guards.  
  
You have to calculate the minimal time to approach Angel. (We can move only UP, DOWN, LEFT and RIGHT, to the neighbor grid within bound, of course.)

## Input

First line contains two integers stand for N and M.  
  
Then N lines follows, every line has M characters. "." stands for road, "a" stands for Angel, and "r" stands for each of Angel's friend.  
  
Process to the end of the file.

## Output

For each test case, your program should output a single integer, standing for the minimal time needed. If such a number does no exist, you should output a line containing "Poor ANGEL has to stay in the prison all his life."

## Sample Input

```
7 8
#.#####.
#.a#..r.
#..#x...
..#..#.#
#...##..
.#......
........

```

## Sample Output

```
13

```

## Author

CHEN, Xue

## Source

[ZOJ Monthly, October 2003](https://acm.hdu.edu.cn//search.php?field=problem&key=ZOJ+Monthly%2C+October+2003&source=1&searchmode=source)
