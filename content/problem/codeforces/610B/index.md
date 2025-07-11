---
title: 【Codeforces】[610B]Vika and Squares
type: post
slug: codeforces-610B
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "Vika and Squares"
    TimeLimit: "2 seconds"
    MemoryLimit: "256 megabytes"
---

## Description

Vika has $n$ jars with paints of distinct colors. All the jars are numbered from $1$ to $n$ and the $i$\-th jar contains $a_{i}$ liters of paint of color $i$.

Vika also has an infinitely long rectangular piece of paper of width $1$, consisting of squares of size $1 × 1$. Squares are numbered $1$, $2$, $3$ and so on. Vika decided that she will start painting squares one by one from left to right, starting from the square number $1$ and some arbitrary color. If the square was painted in color $x$, then the next square will be painted in color $x + 1$. In case of $x = n$, next square is painted in color $1$. If there is no more paint of the color Vika wants to use now, then she stops.

Square is always painted in only one color, and it takes exactly $1$ liter of paint. Your task is to calculate the maximum number of squares that might be painted, if Vika chooses right color to paint the first square.

## Input

The first line of the input contains a single integer $n$ ($1 ≤ n ≤ 200 000$) — the number of jars with colors Vika has.

The second line of the input contains a sequence of integers $a_{1}, a_{2}, ..., a_{n}$ ($1 ≤ a_{i} ≤ 10^{9}$), where $a_{i}$ is equal to the number of liters of paint in the $i$\-th jar, i.e. the number of liters of color $i$ that Vika has.

## Output

The only line of the output should contain a single integer — the maximum number of squares that Vika can paint if she follows the rules described above.

## Examples

### Input

```
5
2 4 2 3 3

```

### Output

```
12

```

### Input

```
3
5 5 5

```

### Output

```
15

```

### Input

```
6
10 10 10 1 10 10

```

### Output

```
11

```

## Note

In the first sample the best strategy is to start painting using color $4$. Then the squares will be painted in the following colors (from left to right): 4, 5, 1, 2, 3, 4, 5, 1, 2, 3, 4, 5.

In the second sample Vika can start to paint using any color.

In the third sample Vika should start painting using color number $5$.
