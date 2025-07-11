---
title: 【Codeforces】[659C]Tanya and Toys
type: post
slug: codeforces-659C
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "Tanya and Toys"
    TimeLimit: "1 second"
    MemoryLimit: "256 megabytes"
---

## Description

In Berland recently a new collection of toys went on sale. This collection consists of $10^{9}$ types of toys, numbered with integers from $1$ to $10^{9}$. A toy from the new collection of the $i$\-th type costs $i$ bourles.

Tania has managed to collect $n$ different types of toys $a_{1}, a_{2}, ..., a_{n}$ from the new collection. Today is Tanya's birthday, and her mother decided to spend no more than $m$ bourles on the gift to the daughter. Tanya will choose several different types of toys from the new collection as a gift. Of course, she does not want to get a type of toy which she already has.

Tanya wants to have as many distinct types of toys in her collection as possible as the result. The new collection is too diverse, and Tanya is too little, so she asks you to help her in this.

## Input

The first line contains two integers $n$ ($1 ≤ n ≤ 100 000$) and $m$ ($1 ≤ m ≤ 10^{9}$) — the number of types of toys that Tanya already has and the number of bourles that her mom is willing to spend on buying new toys.

The next line contains $n$ distinct integers $a_{1}, a_{2}, ..., a_{n}$ ($1 ≤ a_{i} ≤ 10^{9}$) — the types of toys that Tanya already has.

## Output

In the first line print a single integer $k$ — the number of different types of toys that Tanya should choose so that the number of different types of toys in her collection is maximum possible. Of course, the total cost of the selected toys should not exceed $m$.

In the second line print $k$ distinct space-separated integers $t_{1}, t_{2}, ..., t_{k}$ ($1 ≤ t_{i} ≤ 10^{9}$) — the types of toys that Tanya should choose.

If there are multiple answers, you may print any of them. Values of $t_{i}$ can be printed in any order.

## Examples

### Input

```
3 7
1 3 4

```

### Output

```
2
2 5 

```

### Input

```
4 14
4 6 12 8

```

### Output

```
4
7 2 3 1

```

## Note

In the first sample mom should buy two toys: one toy of the $2$\-nd type and one toy of the $5$\-th type. At any other purchase for $7$ bourles (assuming that the toys of types $1$, $3$ and $4$ have already been bought), it is impossible to buy two and more toys.
