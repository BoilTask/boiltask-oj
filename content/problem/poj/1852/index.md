---
title: 【POJ】[1852]Ants
type: post
slug: poj-1852
categories:
  - poj
ProblemParams:
    ProblemTitle: "Ants"
    TimeLimit: "1000MS"
    MemoryLimit: "30000K"
---

## Description

An army of ants walk on a horizontal pole of length l cm, each with a constant speed of 1 cm/s. When a walking ant reaches an end of the pole, it immediatelly falls off it. When two ants meet they turn back and start walking in opposite directions. We know the original positions of ants on the pole, unfortunately, we do not know the directions in which the ants are walking. Your task is to compute the earliest and the latest possible times needed for all ants to fall off the pole.

## Input

The first line of input contains one integer giving the number of cases that follow. The data for each case start with two integer numbers: the length of the pole (in cm) and n, the number of ants residing on the pole. These two numbers are followed by n integers giving the position of each ant on the pole as the distance measured from the left end of the pole, in no particular order. All input integers are not bigger than 1000000 and they are separated by whitespace.

## Output

The first line of input contains one integer giving the number of cases that follow. The data for each case start with two integer numbers: the length of the pole (in cm) and n, the number of ants residing on the pole. These two numbers are followed by n integers giving the position of each ant on the pole as the distance measured from the left end of the pole, in no particular order. All input integers are not bigger than 1000000 and they are separated by whitespace.

## Sample Input

```
2
10 3
2 6 7
214 7
11 12 7 13 176 23 191

```

## Sample Output

```
4 8
38 207

```

## Source

[Waterloo local 2004.09.19](http://poj.org/searchproblem?field=source&key=Waterloo+local+2004.09.19)
