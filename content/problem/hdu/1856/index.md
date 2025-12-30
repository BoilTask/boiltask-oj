---
title: 【HDU】[1856]More is better
type: post
slug: hdu-1856
categories:
  - hdu
ProblemParams:
    ProblemTitle: "More is better"
    TimeLimit: "5000/1000 MS"
    MemoryLimit: "327680/102400 K"
---

## Problem Description

Mr Wang wants some boys to help him with a project. Because the project is rather complex, **the more boys come, the better it will be**. Of course there are certain requirements.  
  
Mr Wang selected a room big enough to hold the boys. The boy who are not been chosen has to leave the room immediately. There are 10000000 boys in the room numbered from 1 to 10000000 at the very beginning. After Mr Wang's selection any two of them who are still in this room should be friends (direct or indirect), or there is only one boy left. Given all the direct friend-pairs, you should decide the best way.

## Input

The first line of the input contains an integer n (0 ≤ n ≤ 100 000) - the number of direct friend-pairs. The following n lines each contains a pair of numbers A and B separated by a single space that suggests A and B are direct friends. (A ≠ B, 1 ≤ A, B ≤ 10000000)

## Output

The output in one line contains exactly one integer equals to the maximum number of boys Mr Wang may keep.

## Sample Input

```
4
1 2
3 4
5 6
1 6
4
1 2
3 4
5 6
7 8

```

## Sample Output

```
4
2

```

## Hint

  
A and B are friends(direct or indirect), B and C are friends(direct or indirect),  
then A and C are also friends(indirect).  
  
In the first sample {1,2,5,6} is the result.  
In the second sample {1,2},{3,4},{5,6},{7,8} are four kinds of answers.

## Author

lxlcrystal@TJU

## Source

[HDU 2007 Programming Contest - Final](https://acm.hdu.edu.cn//search.php?field=problem&key=HDU+2007+Programming+Contest+-+Final&source=1&searchmode=source)
