---
title: 【Codeforces】[606A]Magic Spheres
type: post
slug: codeforces-606A
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "Magic Spheres"
    TimeLimit: "time limit per test"
    MemoryLimit: "memory limit per test"
---

## Description

Carl is a beginner magician. He has _a_ blue, _b_ violet and _c_ orange magic spheres. In one move he can transform two spheres of the same color into one sphere of any other color. To make a spell that has never been seen before, he needs at least _x_ blue, _y_ violet and _z_ orange spheres. Can he get them (possible, in multiple actions)?

## Input

Input

## Output

Output

## Examples

Examples

### Input

```
4 4 0
2 1 2

```

### Output

```
Yes

```

Input

```
5 6 1
2 7 2

```

Output

```
No

```

Input

```
3 3 3
2 2 2

```

Output

```
Yes

```

## Note

Note

In the first sample the wizard has 4 blue and 4 violet spheres. In his first action he can turn two blue spheres into one violet one. After that he will have 2 blue and 5 violet spheres. Then he turns 4 violet spheres into 2 orange spheres and he ends up with 2 blue, 1 violet and 2 orange spheres, which is exactly what he needs.
