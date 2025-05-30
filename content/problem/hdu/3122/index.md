---
title: 【HDU】[3122]FreeRadiant
type: post
slug: hdu-3122
categories:
  - hdu
ProblemParams:
    ProblemTitle: "FreeRadiant"
    TimeLimit: "10000/2000 MS"
    MemoryLimit: "131072/131072 K"
---

## Problem Description

Desolators are the elite troops of the WHU army in the alternate world of ICPC.  
When the Desolator plant a powerful Radiation Cannon in the ground, the cannon emits a radiation field over a circular area with radius R, poisoning everything within the circle (including boundary).The desolator must remain immobile while using this attack; if he wishes to move he has to uproot the cannon, disabling the radiation field. To protect desolator himself from the harm of radiation, the Desolator wears an armored Radiation suit. This suit is protected against the radiation emitted by the cannon.  
There are N enemies need to be destroyed. Each enemy can be destroyed if their total attacked times reach a certain value. Fortunately we know that value for each enemy.  
Our honored desolator FreeRadiant is executing this mission. He can use his cannon freely: e.g. plant it somewhere, wait for some time, uproot it and plant it somewhere else again and so on. The Desolator is so fast that planting, uprooting and moving the cannon takes no time, only the poisoning time matters. He just wants to know the total time needed in which he has to plant the cannon into the ground.

## Input

The first line consists of an integer of T, indicating the test cases in the file.  
Each case begins with two integers, N and R, indicating the number of enemies and the radius of the circle. The next N lines, each line consists of two integers Xi, Yi, Pi, indicating the coordinate and the time needed to destroy each enemy.

## Output

Output one float number rounded to 2 fractional digits, indicating the minimum time for the cannon needs to be planted in the ground.  
Constrains  
T <= 20  
0 < N <= 100 0 < R <= 10000  
0 <= Xi, Yi, Pi <= 10000

## Sample Input

```
2
4 1
1 1 3
1 -1 3
-1 1 3
-1 -1 3
5 1
100 100 10000
1 1 3
1 -1 3
-1 1 3
-1 -1 3

```

## Sample Output

```
6.00
10006.00

```

## Source

[2009 Asia Wuhan Regional Contest Online](https://acm.hdu.edu.cn//search.php?field=problem&key=2009+Asia+Wuhan+Regional+Contest+Online&source=1&searchmode=source)
