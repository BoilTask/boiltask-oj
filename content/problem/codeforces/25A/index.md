---
title: 【Codeforces】[25A]IQ test
type: post
slug: codeforces-25A
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "IQ test"
    TimeLimit: "2 seconds"
    MemoryLimit: "256 megabytes"
---

## Description

Bob is preparing to pass IQ test. The most frequent task in this test is to find out which one of the given $n$ numbers differs from the others. Bob observed that one number usually differs from the others in evenness. Help Bob — to check his answers, he needs a program that among the given $n$ numbers finds one that is different in evenness.

## Input

The first line contains integer $n$ ($3 ≤ n ≤ 100$) — amount of numbers in the task. The second line contains $n$ space-separated natural numbers, not exceeding 100. It is guaranteed, that exactly one of these numbers differs from the others in evenness.

## Output

Output index of number that differs from the others in evenness. Numbers are numbered from 1 in the input order.

## Examples

### Input

```
5
2 4 7 8 10

```

### Output

```
3

```

### Input

```
4
1 2 1 1

```

### Output

```
2

```
