---
title: 【POJ】[1363]Rails
type: post
slug: poj-1363
categories:
  - poj
ProblemParams:
    ProblemTitle: "Rails"
    TimeLimit: "1000MS"
    MemoryLimit: "10000K"
---

## Description

There is a famous railway station in PopPush City. Country there is incredibly hilly. The station was built in last century. Unfortunately, funds were extremely limited that time. It was possible to establish only a surface track. Moreover, it turned out that the station could be only a dead-end one (see picture) and due to lack of available space it could have only one track.  
<div style="text-align: center;"><img src="https://r2-oj.boiltask.com/1363/20ef88ce907a497145f42cae200b2227"></div>  
The local tradition is that every train arriving from the direction A continues in the direction B with coaches reorganized in some way. Assume that the train arriving from the direction A has N <= 1000 coaches numbered in increasing order 1, 2, ..., N. The chief for train reorganizations must know whether it is possible to marshal coaches continuing in the direction B so that their order will be a1, a2, ..., aN. Help him and write a program that decides whether it is possible to get the required order of coaches. You can assume that single coaches can be disconnected from the train before they enter the station and that they can move themselves until they are on the track in the direction B. You can also suppose that at any time there can be located as many coaches as necessary in the station. But once a coach has entered the station it cannot return to the track in the direction A and also once it has left the station in the direction B it cannot return back to the station.

## Input

The input consists of blocks of lines. Each block except the last describes one train and possibly more requirements for its reorganization. In the first line of the block there is the integer N described above. In each of the next lines of the block there is a permutation of 1, 2, ..., N. The last line of the block contains just 0.  
  
The last block consists of just one line containing 0.

## Output

The input consists of blocks of lines. Each block except the last describes one train and possibly more requirements for its reorganization. In the first line of the block there is the integer N described above. In each of the next lines of the block there is a permutation of 1, 2, ..., N. The last line of the block contains just 0.  
  
The last block consists of just one line containing 0.

## Sample Input

```
5
1 2 3 4 5
5 4 1 2 3
0
6
6 5 4 3 2 1
0
0
```

## Sample Output

```
Yes
No

Yes

```

## Source

[Central Europe 1997](https://web.archive.org/web/http://poj.org/searchproblem?field=source&key=Central+Europe+1997)
