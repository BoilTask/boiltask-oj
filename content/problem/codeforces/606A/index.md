---
title: 【Codeforces】[606A]Magic Spheres
type: post
slug: codeforces-606A
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "Magic Spheres"
    TimeLimit: "2 seconds"
    MemoryLimit: "256 megabytes"
---

## Description

<p>Carl is a beginner magician. He has <span class="tex-span"><i>a</i></span> blue, <span class="tex-span"><i>b</i></span> violet and <span class="tex-span"><i>c</i></span> orange magic spheres. In one move he can transform two spheres <span class="tex-font-style-bf">of the same color</span> into one sphere of any other color. To make a spell that has never been seen before, he needs at least <span class="tex-span"><i>x</i></span> blue, <span class="tex-span"><i>y</i></span> violet and <span class="tex-span"><i>z</i></span> orange spheres. Can he get them (possible, in multiple actions)?</p>

## Input

<p>The first line of the input contains three integers <span class="tex-span"><i>a</i></span>, <span class="tex-span"><i>b</i></span> and <span class="tex-span"><i>c</i></span> (<span class="tex-span">0鈥夆墹鈥�<i>a</i>,鈥�<i>b</i>,鈥�<i>c</i>鈥夆墹鈥�1鈥�000鈥�000</span>)聽鈥� the number of blue, violet and orange spheres that are in the magician's disposal.</p><p>The second line of the input contains three integers, <span class="tex-span"><i>x</i></span>, <span class="tex-span"><i>y</i></span> and <span class="tex-span"><i>z</i></span> (<span class="tex-span">0鈥夆墹鈥�<i>x</i>,鈥�<i>y</i>,鈥�<i>z</i>鈥夆墹鈥�1鈥�000鈥�000</span>)聽鈥� the number of blue, violet and orange spheres that he needs to get.</p>

## Output

<p>If the wizard is able to obtain the required numbers of spheres, print "<span class="tex-font-style-tt">Yes</span>". Otherwise, print "<span class="tex-font-style-tt">No</span>".</p>

## Examples

Examples

### Input

```
4 4 0
2 1 2

```

### Output

```
Yes

```

Input

```
5 6 1
2 7 2

```

Output

```
No

```

Input

```
3 3 3
2 2 2

```

Output

```
Yes

```

## Note

Note

In the first sample the wizard has 4 blue and 4 violet spheres. In his first action he can turn two blue spheres into one violet one. After that he will have 2 blue and 5 violet spheres. Then he turns 4 violet spheres into 2 orange spheres and he ends up with 2 blue, 1 violet and 2 orange spheres, which is exactly what he needs.
