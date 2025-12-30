---
title: 【HDU】[4707]Pet
type: post
slug: hdu-4707
categories:
  - hdu
ProblemParams:
    ProblemTitle: "Pet"
    TimeLimit: "4000/2000 MS"
    MemoryLimit: "32768/32768 K"
---

## Problem Description

One day, Lin Ji wake up in the morning and found that his pethamster escaped. He searched in the room but didn’t find the hamster. He tried to use some cheese to trap the hamster. He put the cheese trap in his room and waited for three days. Nothing but cockroaches was caught. He got the map of the school and foundthat there is no cyclic path and every location in the school can be reached from his room. The trap’s manual mention that the pet will always come back if it still in somewhere nearer than distance D. Your task is to help Lin Ji to find out how many possible locations the hamster may found given the map of the school. Assume that the hamster is still hiding in somewhere in the school and distance between each adjacent locations is always one distance unit.

## Input

The input contains multiple test cases. Thefirst line is a positive integer T (0<T<=10), the number of test cases. For each test cases, the first line has two positive integer N (0<N<=100000) and D(0<D<N), separated by a single space. N is the number of locations in the school and D is the affective distance of the trap. The following N-1lines descripts the map, each has two integer x and y(0<=x,y<N), separated by a single space, meaning that x and y is adjacent in the map. Lin Ji’s room is always at location 0.

## Output

For each test case, outputin a single line the number of possible locations in the school the hamster may be found.

## Sample Input

```
1
10 2
0 1
0 2
0 3
1 4
1 5
2 6
3 7
4 8
6 9

```

## Sample Output

```
2

```

## Source

[2013 ACM/ICPC Asia Regional Online —— Warmup](https://acm.hdu.edu.cn//search.php?field=problem&key=2013+ACM%2FICPC+Asia+Regional+Online+%A1%AA%A1%AA+Warmup&source=1&searchmode=source)
