---
title: 【HDU】[2612]Find a way
type: post
slug: hdu-2612
categories:
  - hdu
ProblemParams:
    ProblemTitle: "Find a way"
    TimeLimit: "3000/1000 MS"
    MemoryLimit: "32768/32768 K"
---

## Problem Description

Pass a year learning in Hangzhou, yifenfei arrival hometown Ningbo at finally. Leave Ningbo one year, yifenfei have many people to meet. Especially a good friend Merceki.  
Yifenfei’s home is at the countryside, but Merceki’s home is in the center of city. So yifenfei made arrangements with Merceki to meet at a KFC. There are many KFC in Ningbo, they want to choose one that let the total time to it be most smallest.  
Now give you a Ningbo map, Both yifenfei and Merceki can move up, down ,left, right to the adjacent road by cost 11 minutes.

## Input

The input contains multiple test cases.  
Each test case include, first two integers n, m. (2<=n,m<=200).  
Next n lines, each line included m character.  
‘Y’ express yifenfei initial position.  
‘M’    express Merceki initial position.  
‘#’ forbid road;  
‘.’ Road.  
‘@’ KCF

## Output

For each test case output the minimum total time that both yifenfei and Merceki to arrival one of KFC.You may sure there is always have a KFC that can let them meet.

## Sample Input

```
4 4
Y.#@
....
.#..
@..M
4 4
Y.#@
....
.#..
@#.M
5 5
Y..@.
.#...
.#...
@..M.
#...#

```

## Sample Output

```
66
88
66

```

## Author

yifenfei

## Source

[奋斗的年代](https://acm.hdu.edu.cn//search.php?field=problem&key=%B7%DC%B6%B7%B5%C4%C4%EA%B4%FA&source=1&searchmode=source)
