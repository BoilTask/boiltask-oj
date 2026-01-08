---
title: 【HDU】[5748]Bellovin
type: post
slug: hdu-5748
categories:
  - hdu
ProblemParams:
    ProblemTitle: "Bellovin"
    TimeLimit: "6000/3000 MS"
    MemoryLimit: "131072/131072 K"
---

## Problem Description

Peter has a sequence $a\_1,a\_2,...,a\_n$ and he define a function on the sequence -- $F(a\_1,a\_2,...,a\_n)=(f\_1,f\_2,...,f\_n)$, where $f\_i$ is the length of the longest increasing subsequence ending with $a\_i$.  
  
Peter would like to find another sequence $b\_1,b\_2,...,b\_n$ in such a manner that $F(a\_1,a\_2,...,a\_n)$ equals to $F(b\_1,b\_2,...,b\_n)$. Among all the possible sequences consisting of only positive integers, Peter wants the lexicographically smallest one.  
  
The sequence $a\_1, a\_2, ..., a\_n$ is lexicographically smaller than sequence $b\_1, b\_2, ..., b\_n$, if there is such number $i$ from $1$ to $n$, that $a\_k = b\_k$ for $1 \\le k < i$ and $a\_i < b\_i$.

## Input

There are multiple test cases. The first line of input contains an integer $T$, indicating the number of test cases. For each test case:  
  
The first contains an integer $n$ $(1 \\le n \\le 100000)$ -- the length of the sequence. The second line contains $n$ integers $a\_1,a\_2,...,a\_n$ $(1 \\le a\_i \\le 10^9)$.

## Output

For each test case, output $n$ integers $b\_1,b\_2,...,b\_n$ $(1 \\le b\_i \\le 10^9)$ denoting the lexicographically smallest sequence.

## Sample Input

```
3
1
10
5
5 4 3 2 1
3
1 3 5
```

## Sample Output

```
1
1 1 1 1 1
1 2 3
```

## Source

[BestCoder Round #84](https://acm.hdu.edu.cn//search.php?field=problem&key=BestCoder+Round+%2384&source=1&searchmode=source)
