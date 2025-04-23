---
title: 【Codeforces】[606A]A. Magic Spheres
type: post
slug: codeforces-606A
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "A. Magic Spheres"
    TimeLimit: "time limit per test2 seconds"
    MemoryLimit: "memory limit per test256 megabytes"
---

## Description

Carl is a beginner magician. He has _a_ blue, _b_ violet and _c_ orange magic spheres. In one move he can transform two spheres of the same color into one sphere of any other color. To make a spell that has never been seen before, he needs at least _x_ blue, _y_ violet and _z_ orange spheres. Can he get them (possible, in multiple actions)?

## Input

Input

The first line of the input contains three integers _a_, _b_ and _c_ (0鈥夆墹鈥�_a_,鈥�_b_,鈥�_c_鈥夆墹鈥�1鈥�000鈥�000)聽鈥� the number of blue, violet and orange spheres that are in the magician's disposal.

The second line of the input contains three integers, _x_, _y_ and _z_ (0鈥夆墹鈥�_x_,鈥�_y_,鈥�_z_鈥夆墹鈥�1鈥�000鈥�000)聽鈥� the number of blue, violet and orange spheres that he needs to get.

## Output

Output

If the wizard is able to obtain the required numbers of spheres, print "Yes". Otherwise, print "No".

## Sample Input



## Sample Output



## Note

Note

In the first sample the wizard has 4 blue and 4 violet spheres. In his first action he can turn two blue spheres into one violet one. After that he will have 2 blue and 5 violet spheres. Then he turns 4 violet spheres into 2 orange spheres and he ends up with 2 blue, 1 violet and 2 orange spheres, which is exactly what he needs.
