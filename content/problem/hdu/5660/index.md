---
title: 【HDU】[5660]jrMz and angles
type: post
slug: hdu-5660
categories:
  - hdu
ProblemParams:
    ProblemTitle: "jrMz and angles"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "65536/65536 K"
---

## Problem Description

jrMz has two types of angles, one type of angle is an interior angle of $n$-sided regular polygon, and the other type of angle is an interior angle of $m$-sided regular polygon. jrMz wants to use them to make up an angle of 360 degrees, which means, jrMz needs to choose some or none of the angles which belong to the first type and some or none of the angles which belong to the second type so that the sum value of the angles chosen equals 360 degrees. But jrMz doesn’t know whether it is possible, can you help him?

## Input

The first line contains an integer $T\\left(1\\leq T\\leq10\\right)$——The number of the test cases.  
For each test case, the only line contains two integers $n,m\\left(1\\leq n,m\\leq100\\right)$ with a white space separated.

## Output

For each test case, the only line contains a integer that is the answer.

## Sample Input

```
3
4 8
3 10
5 8

```

## Sample Output

```
Yes
Yes
No
```

## Hint

  
In test case 1, jrMz can choose 1 angle which belongs to the first type and 2 angles which belong to the second type, because 90+135+135=360.  
In test case 2, jrMz can choose 6 angles which belong to the first type, because6\\times60=360.  
In test case 3, jrMz can’t make up an angle of 360 degrees.

## Source

[BestCoder Round #79 (div.2)](https://acm.hdu.edu.cn//search.php?field=problem&key=BestCoder+Round+%2379+%28div.2%29&source=1&searchmode=source)
