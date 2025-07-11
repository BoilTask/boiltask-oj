---
title: 【LightOJ】[1009]Back to Underworld
type: post
slug: lightoj-1009
categories:
  - lightoj
ProblemParams:
    ProblemTitle: "Back to Underworld"
    TimeLimit: "2 seconds"
    MemoryLimit: "64 MB"
---

## Description

The Vampires and Lykans are fighting each other to death. The war has become so fierce that, none knows who will win. The humans want to know who will survive finally. But humans are afraid of going to the battlefield.

So, they made a plan. They collected the information from the newspapers of Vampires and Lykans. They found the information about all the dual fights. Dual fight means a fight between a Lykan and a Vampire. They know the name of the dual fighters, but don't know which one of them is a Vampire or a Lykan.

So, the humans listed all the rivals. They want to find the maximum possible number of Vampires or Lykans.

## Input

Input starts with an integer **T (≤ 10)**, denoting the number of test cases.

Each case contains an integer **n (1 ≤ n ≤ 105)**, denoting the number of dual fights. Each of the next **n** lines will contain two different integers **u v (1 ≤ u, v ≤ 20000)** denoting there was a fight between **u** and **v**. No rival will be reported more than once.

## Output

For each case, print the case number and the maximum possible members of any race.

## Sample Input

```
2
2
1 2
2 3
3
1 2
2 3
4 2

```

## Sample Output

```
Case 1: 2
Case 2: 3

```

## Notes

Dataset is huge, use faster I/O methods.
