---
title: 【Codeforces】[675B]Restoring Painting
type: post
slug: codeforces-675B
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "Restoring Painting"
    TimeLimit: "1 second"
    MemoryLimit: "256 megabytes"
---

## Description

Vasya works as a watchman in the gallery. Unfortunately, one of the most expensive paintings was stolen while he was on duty. He doesn't want to be fired, so he has to quickly restore the painting. He remembers some facts about it.

*   The painting is a square $3 × 3$, each cell contains a single integer from $1$ to $n$, and different cells may contain either different or equal integers.
*   The sum of integers in each of four squares $2 × 2$ is equal to the sum of integers in the top left square $2 × 2$.
*   Four elements $a$, $b$, $c$ and $d$ are known and are located as shown on the picture below.

<div style="text-align: center;"><img class="tex-graphics" src="https://r2-oj.boiltask.com/codeforces-675B/00dc8a667b3c1cef107e1eda42e7e8e6" style="max-width: 100.0%;max-height: 100.0%;"></div>

Help Vasya find out the number of distinct squares the satisfy all the conditions above. Note, that this number may be equal to $0$, meaning Vasya remembers something wrong.

Two squares are considered to be different, if there exists a cell that contains two different integers in different squares.

## Input

The first line of the input contains five integers $n$, $a$, $b$, $c$ and $d$ ($1 ≤ n ≤ 100 000$, $1 ≤ a, b, c, d ≤ n$) — maximum possible value of an integer in the cell and four integers that Vasya remembers.

## Output

Print one integer — the number of distinct valid squares.

## Examples

### Input

```
2 1 1 1 2

```

### Output

```
2

```

### Input

```
3 3 1 2 3

```

### Output

```
6

```

## Note

Below are all the possible paintings for the first sample. ![](https://r2-oj.boiltask.com/codeforces-675B/1b88bc3de95c1accb24b5ee23983e3eb) ![](https://r2-oj.boiltask.com/codeforces-675B/326bd412d88fbbef68a1f5c8515a7558)

In the second sample, only paintings displayed below satisfy all the rules. ![](https://r2-oj.boiltask.com/codeforces-675B/fddbb05767e29b1d3c0d314c06024d84) ![](https://r2-oj.boiltask.com/codeforces-675B/73581e006f2385dd32fd156d08d7ea86) ![](https://r2-oj.boiltask.com/codeforces-675B/f832ddd3d2a0e5d342e1f1b70f6750ff) ![](https://r2-oj.boiltask.com/codeforces-675B/b00e35b16dc3f48d84133f5ff346cb1e) ![](https://r2-oj.boiltask.com/codeforces-675B/3804065a5dbb5c9e140d36f2267c7148) ![](https://r2-oj.boiltask.com/codeforces-675B/f8a680555bd0d702b2981558330652b2)
