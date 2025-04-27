---
title: 【POJ】[2631]Roads in the North
type: post
slug: poj-2631
categories:
  - poj
ProblemParams:
    ProblemTitle: "Roads in the North"
    TimeLimit: "1000MS"
    MemoryLimit: "65536K"
---

## Description

Building and maintaining roads among communities in the far North is an expensive business. With this in mind, the roads are build such that there is only one route from a village to a village that does not pass through some other village twice.  
Given is an area in the far North comprising a number of villages and roads among them such that any village can be reached by road from any other village. Your job is to find the road distance between the two most remote villages in the area.  
  
The area has up to 10,000 villages connected by road segments. The villages are numbered from 1.

## Input

Input to the problem is a sequence of lines, each containing three positive integers: the number of a village, the number of a different village, and the length of the road segment connecting the villages in kilometers. All road segments are two-way.

## Output

Input to the problem is a sequence of lines, each containing three positive integers: the number of a village, the number of a different village, and the length of the road segment connecting the villages in kilometers. All road segments are two-way.

## Sample Input

```
5 1 6
1 4 5
6 3 9
2 6 8
6 1 7

```

## Sample Output

```
22
```

## Source

[The UofA Local 1999.10.16](http://poj.org/searchproblem?field=source&key=The+UofA+Local+1999.10.16)
