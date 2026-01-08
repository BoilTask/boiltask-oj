---
title: 【LightOJ】[1198]Karate Competition
type: post
slug: lightoj-1198
categories:
  - lightoj
ProblemParams:
    ProblemTitle: "Karate Competition"
    TimeLimit: "1 seconds"
    MemoryLimit: "64 MB"
---

## Description

Your karate club challenged another karate club in your town. Each club enters **N** players into the match, and each player plays one game against a player from the other team. Each game that is won is worth **2** points, and each game that is drawn is worth **1** point. Your goal is to score as many points as possible.

Your secret agents have determined the skill of every member of the opposing team, and of course you know the skill of every member of your own team. You can use this information to decide which opposing player will play against each of your players in order to maximize your score. Assume that the player with the higher skill in a game will always win, and if the players have the same skill then they will draw.

You will be given the skills of your players and of the opposing players, you have to find the maximum number of points that your team can score.

## Input

Input starts with an integer **T (≤ 70)**, denoting the number of test cases.

Each case starts with a line containing an integer **N (1 ≤ N ≤ 50)**. The next line contains **N** space separated integers denoting the skills of the players of your team. The next line also contains **N** space separated integers denoting the skills of the players of the opposite team. Each of the skills lies in the range **\[1, 1000\]**.

## Output

For each case, print the case number and the maximum number of points your team can score.

## Sample Input

```
4
2
4 7
6 2
2
6 2
4 7
3
5 10 1
5 10 1
4
10 7 1 4
15 3 8 7

```

## Sample Output

```
Case 1: 4
Case 2: 2
Case 3: 4
Case 4: 5

```
