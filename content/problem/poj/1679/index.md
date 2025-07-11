---
title: 【POJ】[1679]The Unique MST
type: post
slug: poj-1679
categories:
  - poj
ProblemParams:
    ProblemTitle: "The Unique MST"
    TimeLimit: "1000MS"
    MemoryLimit: "10000K"
---

## Description

Given a connected undirected graph, tell if its minimum spanning tree is unique.  
  
Definition 1 (Spanning Tree): Consider a connected, undirected graph G = (V, E). A spanning tree of G is a subgraph of G, say T = (V', E'), with the following properties:  
1\. V' = V.  
2\. T is connected and acyclic.  
  
Definition 2 (Minimum Spanning Tree): Consider an edge-weighted, connected, undirected graph G = (V, E). The minimum spanning tree T = (V, E') of G is the spanning tree that has the smallest total cost. The total cost of T means the sum of the weights on all the edges in E'.

## Input

The first line contains a single integer t (1 <= t <= 20), the number of test cases. Each case represents a graph. It begins with a line containing two integers n and m (1 <= n <= 100), the number of nodes and edges. Each of the following m lines contains a triple (xi, yi, wi), indicating that xi and yi are connected by an edge with weight = wi. For any two nodes, there is at most one edge connecting them.

## Output

The first line contains a single integer t (1 <= t <= 20), the number of test cases. Each case represents a graph. It begins with a line containing two integers n and m (1 <= n <= 100), the number of nodes and edges. Each of the following m lines contains a triple (xi, yi, wi), indicating that xi and yi are connected by an edge with weight = wi. For any two nodes, there is at most one edge connecting them.

## Sample Input

```
2
3 3
1 2 1
2 3 2
3 1 3
4 4
1 2 2
2 3 2
3 4 2
4 1 2

```

## Sample Output

```
3
Not Unique!

```

## Source

[POJ Monthly--2004.06.27 srbga@POJ](http://poj.org/searchproblem?field=source&key=POJ+Monthly--2004.06.27+srbga%40POJ)
