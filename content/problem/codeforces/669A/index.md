---
title: 【Codeforces】[669A]Little Artem and Presents
type: post
slug: codeforces-669A
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "Little Artem and Presents"
    TimeLimit: "2 seconds"
    MemoryLimit: "256 megabytes"
---

## Description

Little Artem got $n$ stones on his birthday and now wants to give some of them to Masha. He knows that Masha cares more about the fact of receiving the present, rather than the value of that present, so he wants to give her stones as many times as possible. However, Masha remembers the last present she received, so Artem can't give her the same number of stones twice in a row. For example, he can give her $3$ stones, then $1$ stone, then again $3$ stones, but he can't give her $3$ stones and then again $3$ stones right after that.

How many times can Artem give presents to Masha?

## Input

The only line of the input contains a single integer $n$ ($1 ≤ n ≤ 10^{9}$) — number of stones Artem received on his birthday.

## Output

Print the maximum possible number of times Artem can give presents to Masha.

## Examples

### Input

```
1

```

### Output

```
1

```

### Input

```
2

```

### Output

```
1

```

### Input

```
3

```

### Output

```
2

```

### Input

```
4

```

### Output

```
3

```

## Note

In the first sample, Artem can only give $1$ stone to Masha.

In the second sample, Atrem can give Masha $1$ or $2$ stones, though he can't give her $1$ stone two times.

In the third sample, Atrem can first give Masha $2$ stones, a then $1$ more stone.

In the fourth sample, Atrem can first give Masha $1$ stone, then $2$ stones, and finally $1$ stone again.
