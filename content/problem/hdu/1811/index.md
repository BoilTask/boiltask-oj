---
title: 【HDU】[1811]Rank of Tetris
type: post
slug: hdu-1811
categories:
  - hdu
ProblemParams:
    ProblemTitle: "Rank of Tetris"
    TimeLimit: "1000/1000 MS"
    MemoryLimit: "32768/32768 K"
---

## Problem Description

自从Lele开发了Rating系统，他的Tetris事业更是如虎添翼，不久他遍把这个游戏推向了全球。  
  
为了更好的符合那些爱好者的喜好，Lele又想了一个新点子：他将制作一个全球Tetris高手排行榜，定时更新，名堂要比福布斯富豪榜还响。关于如何排名，这个不用说都知道是根据Rating从高到低来排，如果两个人具有相同的Rating，那就按这几个人的RP从高到低来排。  
  
终于，Lele要开始行动了，对N个人进行排名。为了方便起见，每个人都已经被编号，分别从0到N-1,并且编号越大，RP就越高。  
同时Lele从狗仔队里取得一些（M个）关于Rating的信息。这些信息可能有三种情况，分别是"A > B","A = B","A < B"，分别表示A的Rating高于B,等于B,小于B。  
  
现在Lele并不是让你来帮他制作这个高手榜，他只是想知道，根据这些信息是否能够确定出这个高手榜，是的话就输出"OK"。否则就请你判断出错的原因，到底是因为信息不完全（输出"UNCERTAIN"），还是因为这些信息中包含冲突（输出"CONFLICT"）。  
注意，如果信息中同时包含冲突且信息不完全，就输出"CONFLICT"。

## Input

本题目包含多组测试，请处理到文件结束。  
每组测试第一行包含两个整数N,M(0<=N<=10000,0<=M<=20000),分别表示要排名的人数以及得到的关系数。  
接下来有M行，分别表示这些关系

## Output

对于每组测试，在一行里按题目要求输出

## Sample Input

```
3 3
0 &gt; 1
1 &lt; 2
0 &gt; 2
4 4
1 = 2
1 &gt; 3
2 &gt; 0
0 &gt; 1
3 3
1 &gt; 0
1 &gt; 2
2 &lt; 1

```

## Sample Output

```
OK
CONFLICT
UNCERTAIN

```

## Author

linle

## Source

[HDOJ 2007 Summer Exercise（2）](https://acm.hdu.edu.cn//search.php?field=problem&key=HDOJ+2007+Summer+Exercise%A3%A82%A3%A9&source=1&searchmode=source)
