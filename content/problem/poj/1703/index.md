---
title: 【POJ】[1703]Find them, Catch them
type: post
slug: poj-1703
categories:
  - poj
ProblemParams:
    ProblemTitle: "Find them, Catch them"
    TimeLimit: "1000MS"
    MemoryLimit: "10000K"
---

## Description

The police office in Tadu City decides to say ends to the chaos, as launch actions to root up the TWO gangs in the city, Gang Dragon and Gang Snake. However, the police first needs to identify which gang a criminal belongs to. The present question is, given two criminals; do they belong to a same clan? You must give your judgment based on incomplete information. (Since the gangsters are always acting secretly.)  
  
Assume N (N <= 10^5) criminals are currently in Tadu City, numbered from 1 to N. And of course, at least one of them belongs to Gang Dragon, and the same for Gang Snake. You will be given M (M <= 10^5) messages in sequence, which are in the following two kinds:  
  
1\. D \[a\] \[b\]  
where \[a\] and \[b\] are the numbers of two criminals, and they belong to different gangs.  
  
2\. A \[a\] \[b\]  
where \[a\] and \[b\] are the numbers of two criminals. This requires you to decide whether a and b belong to a same gang.

## Input

The first line of the input contains a single integer T (1 <= T <= 20), the number of test cases. Then T cases follow. Each test case begins with a line with two integers N and M, followed by M lines each containing one message as described above.

## Output

The first line of the input contains a single integer T (1 <= T <= 20), the number of test cases. Then T cases follow. Each test case begins with a line with two integers N and M, followed by M lines each containing one message as described above.

## Sample Input

```
1
5 5
A 1 2
D 1 2
A 1 2
D 2 4
A 1 4

```

## Sample Output

```
Not sure yet.
In different gangs.
In the same gang.

```

## Source

[POJ Monthly--2004.07.18](http://poj.org/searchproblem?field=source&key=POJ+Monthly--2004.07.18)
