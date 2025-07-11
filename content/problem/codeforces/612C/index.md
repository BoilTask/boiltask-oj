---
title: 【Codeforces】[612C]Replace To Make Regular Bracket Sequence
type: post
slug: codeforces-612C
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "Replace To Make Regular Bracket Sequence"
    TimeLimit: "1 second"
    MemoryLimit: "256 megabytes"
---

## Description

You are given string $s$ consists of opening and closing brackets of four kinds <>, {}, \[\], (). There are two types of brackets: opening and closing. You can replace any bracket by another of the same type. For example, you can replace < by the bracket {, but you can't replace it by ) or \>.

The following definition of a regular bracket sequence is well-known, so you can be familiar with it.

Let's define a regular bracket sequence (RBS). Empty string is RBS. Let $s_{1}$ and $s_{2}$ be a RBS then the strings <$s_{1}$\>$s_{2}$, {$s_{1}$}$s_{2}$, \[$s_{1}$\]$s_{2}$, ($s_{1}$)$s_{2}$ are also RBS.

For example the string "\[\[(){}\]<>\]" is RBS, but the strings "\[)()" and "\]\[()()" are not.

Determine the least number of replaces to make the string $s$ RBS.

## Input

The only line contains a non empty string $s$, consisting of only opening and closing brackets of four kinds. The length of $s$ does not exceed $10^{6}$.

## Output

If it's impossible to get RBS from $s$ print Impossible.

Otherwise print the least number of replaces needed to get RBS from $s$.

## Examples

### Input

```
[&lt;}){}

```

### Output

```
2
```

### Input

```
{()}[]

```

### Output

```
0
```

### Input

```
]]

```

### Output

```
Impossible
```
