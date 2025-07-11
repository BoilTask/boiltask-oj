---
title: 【Codeforces】[667A]Pouring Rain
type: post
slug: codeforces-667A
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "Pouring Rain"
    TimeLimit: "1 second"
    MemoryLimit: "256 megabytes"
---

## Description

A lot of people in Berland hates rain, but you do not. Rain pacifies, puts your thoughts in order. By these years you have developed a good tradition — when it rains, you go on the street and stay silent for a moment, contemplate all around you, enjoy freshness, think about big deeds you have to do.

Today everything had changed quietly. You went on the street with a cup contained water, your favorite drink. In a moment when you were drinking a water you noticed that the process became quite long: the cup still contained water because of rain. You decided to make a formal model of what was happening and to find if it was possible to drink all water in that situation.

Thus, your cup is a cylinder with diameter equals $d$ centimeters. Initial level of water in cup equals $h$ centimeters from the bottom.

<div style="text-align: center;"><img class="tex-graphics" src="https://r2-oj.boiltask.com/codeforces-667A/57a6a8e5c53b89cd046a3d78485af153" style="max-width: 100.0%;max-height: 100.0%;"></div>

You drink a water with a speed equals $v$ milliliters per second. But rain goes with such speed that if you do not drink a water from the cup, the level of water increases on $e$ centimeters per second. The process of drinking water from the cup and the addition of rain to the cup goes evenly and continuously.

Find the time needed to make the cup empty or find that it will never happen. It is guaranteed that if it is possible to drink all water, it will happen not later than after $10^{4}$ seconds.

Note one milliliter equals to one cubic centimeter.

## Input

The only line of the input contains four integer numbers $d, h, v, e$ ($1 ≤ d, h, v, e ≤ 10^{4}$), where:

*   $d$ — the diameter of your cylindrical cup,
*   $h$ — the initial level of water in the cup,
*   $v$ — the speed of drinking process from the cup in milliliters per second,
*   $e$ — the growth of water because of rain if you do not drink from the cup.

## Output

If it is impossible to make the cup empty, print "NO" (without quotes).

Otherwise print "YES" (without quotes) in the first line. In the second line print a real number — time in seconds needed the cup will be empty. The answer will be considered correct if its relative or absolute error doesn't exceed $10^{ - 4}$. It is guaranteed that if the answer exists, it doesn't exceed $10^{4}$.

## Examples

### Input

```
1 2 3 100

```

### Output

```
NO

```

### Input

```
1 1 1 1

```

### Output

```
YES
3.659792366325

```

## Note

In the first example the water fills the cup faster than you can drink from it.

In the second example area of the cup's bottom equals to ![](https://r2-oj.boiltask.com/codeforces-667A/8a6332242dd22ab4d0835a036e0cec4d), thus we can conclude that you decrease the level of water by ![](https://r2-oj.boiltask.com/codeforces-667A/228bca3cb10acb1cd638f1bbf282808b) centimeters per second. At the same time water level increases by $1$ centimeter per second due to rain. Thus, cup will be empty in ![](https://r2-oj.boiltask.com/codeforces-667A/2a1adecea9b4fcf367c4d7f9a31b063c) seconds.
