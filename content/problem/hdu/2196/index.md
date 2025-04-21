---
title: 【HDU】[2196]Computer
type: post
slug: hdu-2196
categories:
  - hdu
---

# Computer

## Problem Description

A school bought the first computer some time ago(so this computer's id is 1). During the recent years the school bought N-1 new computers. Each new computer was connected to one of settled earlier. Managers of school are anxious about slow functioning of the net and want to know the maximum distance Si for which i-th computer needs to send signal (i.e. length of cable to the most distant computer). You need to provide this information.  

![](../../../data/images/C128-1005-1.JPG)

  
  
Hint: the example input is corresponding to this graph. And from the graph, you can see that the computer 4 is farthest one from 1, so S1 = 3. Computer 4 and 5 are the farthest ones from 2, so S2 = 2. Computer 5 is the farthest one from 3, so S3 = 3. we also get S4 = 4, S5 = 4.

## Input

Input file contains multiple test cases.In each case there is natural number N (N<=10000) in the first line, followed by (N-1) lines with descriptions of computers. i-th line contains two natural numbers - number of computer, to which i-th computer is connected and length of cable used for connection. Total length of cable does not exceed 10^9. Numbers in lines of input are separated by a space.

## Output

For each case output N lines. i-th line must contain number Si for i-th computer (1<=i<=N).

## Sample Input

```
5
1 1
2 1
3 1
1 1

```

## Sample Output

```
3
2
3
4
4

```

## Author

scnu
