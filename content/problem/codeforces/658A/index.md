---
title: 【Codeforces】[658A]Bear and Reverse Radewoosh
type: post
slug: codeforces-658A
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "Bear and Reverse Radewoosh"
    TimeLimit: "2 seconds"
    MemoryLimit: "256 megabytes"
---

## Description

Limak and Radewoosh are going to compete against each other in the upcoming algorithmic contest. They are equally skilled but they won't solve problems in the same order.

There will be $n$ problems. The $i$\-th problem has initial score $p_{i}$ and it takes exactly $t_{i}$ minutes to solve it. Problems are sorted by difficulty — it's guaranteed that $p_{i} < p_{i + 1}$ and $t_{i} < t_{i + 1}$.

A constant $c$ is given too, representing the speed of loosing points. Then, submitting the $i$\-th problem at time $x$ ($x$ minutes after the start of the contest) gives $max(0,  p_{i} - c·x)$ points.

Limak is going to solve problems in order $1, 2, ..., n$ (sorted increasingly by $p_{i}$). Radewoosh is going to solve them in order $n, n - 1, ..., 1$ (sorted decreasingly by $p_{i}$). Your task is to predict the outcome — print the name of the winner (person who gets more points at the end) or a word "Tie" in case of a tie.

You may assume that the duration of the competition is greater or equal than the sum of all $t_{i}$. That means both Limak and Radewoosh will accept all $n$ problems.

## Input

The first line contains two integers $n$ and $c$ ($1 ≤ n ≤ 50, 1 ≤ c ≤ 1000$) — the number of problems and the constant representing the speed of loosing points.

The second line contains $n$ integers $p_{1}, p_{2}, ..., p_{n}$ ($1 ≤ p_{_{i}} ≤ 1000, pi < p_{i + 1}$) — initial scores.

The third line contains $n$ integers $t_{1}, t_{2}, ..., t_{n}$ ($1 ≤ t_{_{i}} ≤ 1000, ti < t_{i + 1}$) where $t_{i}$ denotes the number of minutes one needs to solve the $i$\-th problem.

## Output

Print "Limak" (without quotes) if Limak will get more points in total. Print "Radewoosh" (without quotes) if Radewoosh will get more points in total. Print "Tie" (without quotes) if Limak and Radewoosh will get the same total number of points.

## Examples

### Input

```
3 2
50 85 250
10 15 25

```

### Output

```
Limak

```

### Input

```
3 6
50 85 250
10 15 25

```

### Output

```
Radewoosh

```

### Input

```
8 1
10 20 30 40 50 60 70 80
8 10 58 63 71 72 75 76

```

### Output

```
Tie

```

## Note

In the first sample, there are $3$ problems. Limak solves them as follows:

1.  Limak spends $10$ minutes on the $1$\-st problem and he gets $50 - c·10 = 50 - 2·10 = 30$ points.
2.  Limak spends $15$ minutes on the $2$\-nd problem so he submits it $10 + 15 = 25$ minutes after the start of the contest. For the $2$\-nd problem he gets $85 - 2·25 = 35$ points.
3.  He spends $25$ minutes on the $3$\-rd problem so he submits it $10 + 15 + 25 = 50$ minutes after the start. For this problem he gets $250 - 2·50 = 150$ points.

So, Limak got $30 + 35 + 150 = 215$ points.

Radewoosh solves problem in the reversed order:

1.  Radewoosh solves $3$\-rd problem after $25$ minutes so he gets $250 - 2·25 = 200$ points.
2.  He spends $15$ minutes on the $2$\-nd problem so he submits it $25 + 15 = 40$ minutes after the start. He gets $85 - 2·40 = 5$ points for this problem.
3.  He spends $10$ minutes on the $1$\-st problem so he submits it $25 + 15 + 10 = 50$ minutes after the start. He gets $max(0, 50 - 2·50) = max(0,  - 50) = 0$ points.

Radewoosh got $200 + 5 + 0 = 205$ points in total. Limak has $215$ points so Limak wins.

In the second sample, Limak will get $0$ points for each problem and Radewoosh will first solve the hardest problem and he will get $250 - 6·25 = 100$ points for that. Radewoosh will get $0$ points for other two problems but he is the winner anyway.

In the third sample, Limak will get $2$ points for the $1$\-st problem and $2$ points for the $2$\-nd problem. Radewoosh will get $4$ points for the $8$\-th problem. They won't get points for other problems and thus there is a tie because $2 + 2 = 4$.
