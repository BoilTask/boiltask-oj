---
title: 【POJ】[2349]Arctic Network
type: post
slug: poj-2349
categories:
  - poj
ProblemParams:
    ProblemTitle: "Arctic Network"
    TimeLimit: "2000MS"
    MemoryLimit: "65536K"
---

## Description

The Department of National Defence (DND) wishes to connect several northern outposts by a wireless network. Two different communication technologies are to be used in establishing the network: every outpost will have a radio transceiver and some outposts will in addition have a satellite channel.  
Any two outposts with a satellite channel can communicate via the satellite, regardless of their location. Otherwise, two outposts can communicate by radio only if the distance between them does not exceed D, which depends of the power of the transceivers. Higher power yields higher D but costs more. Due to purchasing and maintenance considerations, the transceivers at the outposts must be identical; that is, the value of D is the same for every pair of outposts.  
  
Your job is to determine the minimum D required for the transceivers. There must be at least one communication path (direct or indirect) between every pair of outposts.

## Input

The first line of input contains N, the number of test cases. The first line of each test case contains 1 <= S <= 100, the number of satellite channels, and S < P <= 500, the number of outposts. P lines follow, giving the (x,y) coordinates of each outpost in km (coordinates are integers between 0 and 10,000).

## Output

The first line of input contains N, the number of test cases. The first line of each test case contains 1 <= S <= 100, the number of satellite channels, and S < P <= 500, the number of outposts. P lines follow, giving the (x,y) coordinates of each outpost in km (coordinates are integers between 0 and 10,000).

## Sample Input

```
1
2 4
0 100
0 300
0 600
150 750

```

## Sample Output

```
212.13

```

## Source

[Waterloo local 2002.09.28](https://web.archive.org/web/http://poj.org/searchproblem?field=source&key=Waterloo+local+2002.09.28)
