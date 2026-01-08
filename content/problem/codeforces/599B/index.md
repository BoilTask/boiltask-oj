---
title: 【Codeforces】[599B]Spongebob and Joke
type: post
slug: codeforces-599B
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "Spongebob and Joke"
    TimeLimit: "2 seconds"
    MemoryLimit: "256 megabytes"
---

## Description

While Patrick was gone shopping, Spongebob decided to play a little trick on his friend. The naughty Sponge browsed through Patrick's personal stuff and found a sequence $a_{1}, a_{2}, ..., a_{m}$ of length $m$, consisting of integers from $1$ to $n$, not necessarily distinct. Then he picked some sequence $f_{1}, f_{2}, ..., f_{n}$ of length $n$ and for each number $a_{i}$ got number $b_{_{i}} = f_{ai}$. To finish the prank he erased the initial sequence $a_{i}$.

It's hard to express how sad Patrick was when he returned home from shopping! We will just say that Spongebob immediately got really sorry about what he has done and he is now trying to restore the original sequence. Help him do this or determine that this is impossible.

## Input

The first line of the input contains two integers $n$ and $m$ ($1 ≤ n, m ≤ 100 000$) — the lengths of sequences $f_{i}$ and $b_{i}$ respectively.

The second line contains $n$ integers, determining sequence $f_{1}, f_{2}, ..., f_{n}$ ($1 ≤ f_{i} ≤ n$).

The last line contains $m$ integers, determining sequence $b_{1}, b_{2}, ..., b_{m}$ $(1 ≤ b_{i} ≤ n)$.

## Output

Print "Possible" if there is exactly one sequence $a_{i}$, such that $b_{_{i}} = f_{ai}$ for all $i$ from $1$ to $m$. Then print $m$ integers $a_{1}, a_{2}, ..., a_{m}$.

If there are multiple suitable sequences $a_{i}$, print "Ambiguity".

If Spongebob has made a mistake in his calculations and no suitable sequence $a_{i}$ exists, print "Impossible".

## Examples

### Input

```
3 3
3 2 1
1 2 3

```

### Output

```
Possible
3 2 1 

```

### Input

```
3 3
1 1 1
1 1 1

```

### Output

```
Ambiguity

```

### Input

```
3 3
1 2 1
3 3 3

```

### Output

```
Impossible

```

## Note

In the first sample $3$ is replaced by $1$ and vice versa, while $2$ never changes. The answer exists and is unique.

In the second sample all numbers are replaced by $1$, so it is impossible to unambiguously restore the original sequence.

In the third sample $f_{i} ≠ 3$ for all $i$, so no sequence $a_{i}$ transforms into such $b_{i}$ and we can say for sure that Spongebob has made a mistake.
