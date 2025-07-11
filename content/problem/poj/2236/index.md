---
title: 【POJ】[2236]Wireless Network
type: post
slug: poj-2236
categories:
  - poj
ProblemParams:
    ProblemTitle: "Wireless Network"
    TimeLimit: "10000MS"
    MemoryLimit: "65536K"
---

## Description

An earthquake takes place in Southeast Asia. The ACM (Asia Cooperated Medical team) have set up a wireless network with the lap computers, but an unexpected aftershock attacked, all computers in the network were all broken. The computers are repaired one by one, and the network gradually began to work again. Because of the hardware restricts, each computer can only directly communicate with the computers that are not farther than d meters from it. But every computer can be regarded as the intermediary of the communication between two other computers, that is to say computer A and computer B can communicate if computer A and computer B can communicate directly or there is a computer C that can communicate with both A and B.  
  
In the process of repairing the network, workers can take two kinds of operations at every moment, repairing a computer, or testing if two computers can communicate. Your job is to answer all the testing operations.

## Input

The first line contains two integers N and d (1 <= N <= 1001, 0 <= d <= 20000). Here N is the number of computers, which are numbered from 1 to N, and D is the maximum distance two computers can communicate directly. In the next N lines, each contains two integers xi, yi (0 <= xi, yi <= 10000), which is the coordinate of N computers. From the (N+1)-th line to the end of input, there are operations, which are carried out one by one. Each line contains an operation in one of following two formats:  
1\. "O p" (1 <= p <= N), which means repairing computer p.  
2\. "S p q" (1 <= p, q <= N), which means testing whether computer p and q can communicate.  
  
The input will not exceed 300000 lines.

## Output

The first line contains two integers N and d (1 <= N <= 1001, 0 <= d <= 20000). Here N is the number of computers, which are numbered from 1 to N, and D is the maximum distance two computers can communicate directly. In the next N lines, each contains two integers xi, yi (0 <= xi, yi <= 10000), which is the coordinate of N computers. From the (N+1)-th line to the end of input, there are operations, which are carried out one by one. Each line contains an operation in one of following two formats:  
1\. "O p" (1 <= p <= N), which means repairing computer p.  
2\. "S p q" (1 <= p, q <= N), which means testing whether computer p and q can communicate.  
  
The input will not exceed 300000 lines.

## Sample Input

```
4 1
0 1
0 2
0 3
0 4
O 1
O 2
O 4
S 1 4
O 3
S 1 4

```

## Sample Output

```
FAIL
SUCCESS

```

## Source

[POJ Monthly](http://poj.org/searchproblem?field=source&key=POJ+Monthly),HQM
