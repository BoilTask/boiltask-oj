---
title: 【HDU】[5583]Kingdom of Black and White
type: post
slug: hdu-5583
categories:
  - hdu
ProblemParams:
    ProblemTitle: "Kingdom of Black and White"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "65536/65536 K"
---

## Problem Description

In the Kingdom of Black and White (KBW), there are two kinds of frogs: black frog and white frog.  
  
Now $N$ frogs are standing in a line, some of them are black, the others are white. The total strength of those frogs are calculated by dividing the line into minimum parts, each part should still be continuous, and can only contain one kind of frog. Then the strength is the sum of the squared length for each part.  
  
However, an old, evil witch comes, and tells the frogs that she will change the color of **at most one** frog and thus the strength of those frogs might change.  
  
The frogs wonder the **maximum** possible strength after the witch finishes her job.

## Input

First line contains an integer $T$, which indicates the number of test cases.  
  
Every test case only contains a string with length $N$, including only $0$ (representing  
a black frog) and $1$ (representing a white frog).  
  
$\\cdot$ $1 \\leq T \\leq 50$.  
  
$\\cdot$ for 60% data, $1 \\leq N \\leq 1000$.  
  
$\\cdot$ for 100% data, $1 \\leq N \\leq 10^5$.  
  
$\\cdot$ the string only contains 0 and 1.

## Output

For every test case, you should output "**Case #x: y**",where $x$ indicates the case number and counts from $1$ and $y$ is the answer.

## Sample Input

```
2
000011
0101
```

## Sample Output

```
Case #1: 26
Case #2: 10
```

## Source

[2015ACM/ICPC亚洲区上海站-重现赛（感谢华东理工）](https://acm.hdu.edu.cn//search.php?field=problem&key=2015ACM%2FICPC%D1%C7%D6%DE%C7%F8%C9%CF%BA%A3%D5%BE-%D6%D8%CF%D6%C8%FC%A3%A8%B8%D0%D0%BB%BB%AA%B6%AB%C0%ED%B9%A4%A3%A9&source=1&searchmode=source)
