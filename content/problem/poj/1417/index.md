---
title: 【POJ】[1417]True Liars
type: post
slug: poj-1417
categories:
  - poj
ProblemParams:
    ProblemTitle: "True Liars"
    TimeLimit: "1000MS"
    MemoryLimit: "10000K"
---

## Description

After having drifted about in a small boat for a couple of days, Akira Crusoe Maeda was finally cast ashore on a foggy island. Though he was exhausted and despaired, he was still fortunate to remember a legend of the foggy island, which he had heard from patriarchs in his childhood. This must be the island in the legend. In the legend, two tribes have inhabited the island, one is divine and the other is devilish, once members of the divine tribe bless you, your future is bright and promising, and your soul will eventually go to Heaven, in contrast, once members of the devilish tribe curse you, your future is bleak and hopeless, and your soul will eventually fall down to Hell.  
  
In order to prevent the worst-case scenario, Akira should distinguish the devilish from the divine. But how? They looked exactly alike and he could not distinguish one from the other solely by their appearances. He still had his last hope, however. The members of the divine tribe are truth-tellers, that is, they always tell the truth and those of the devilish tribe are liars, that is, they always tell a lie.  
  
He asked some of them whether or not some are divine. They knew one another very much and always responded to him "faithfully" according to their individual natures (i.e., they always tell the truth or always a lie). He did not dare to ask any other forms of questions, since the legend says that a devilish member would curse a person forever when he did not like the question. He had another piece of useful informationf the legend tells the populations of both tribes. These numbers in the legend are trustworthy since everyone living on this island is immortal and none have ever been born at least these millennia.  
  
You are a good computer programmer and so requested to help Akira by writing a program that classifies the inhabitants according to their answers to his inquiries.

## Input

The input consists of multiple data sets, each in the following format :  
  
n p1 p2  
xl yl a1  
x2 y2 a2  
...  
xi yi ai  
...  
xn yn an  
  
The first line has three non-negative integers n, p1, and p2. n is the number of questions Akira asked. pl and p2 are the populations of the divine and devilish tribes, respectively, in the legend. Each of the following n lines has two integers xi, yi and one word ai. xi and yi are the identification numbers of inhabitants, each of which is between 1 and p1 + p2, inclusive. ai is either yes, if the inhabitant xi said that the inhabitant yi was a member of the divine tribe, or no, otherwise. Note that xi and yi can be the same number since "are you a member of the divine tribe?" is a valid question. Note also that two lines may have the same x's and y's since Akira was very upset and might have asked the same question to the same one more than once.  
  
You may assume that n is less than 1000 and that p1 and p2 are less than 300. A line with three zeros, i.e., 0 0 0, represents the end of the input. You can assume that each data set is consistent and no contradictory answers are included.

## Output

The input consists of multiple data sets, each in the following format :  
  
n p1 p2  
xl yl a1  
x2 y2 a2  
...  
xi yi ai  
...  
xn yn an  
  
The first line has three non-negative integers n, p1, and p2. n is the number of questions Akira asked. pl and p2 are the populations of the divine and devilish tribes, respectively, in the legend. Each of the following n lines has two integers xi, yi and one word ai. xi and yi are the identification numbers of inhabitants, each of which is between 1 and p1 + p2, inclusive. ai is either yes, if the inhabitant xi said that the inhabitant yi was a member of the divine tribe, or no, otherwise. Note that xi and yi can be the same number since "are you a member of the divine tribe?" is a valid question. Note also that two lines may have the same x's and y's since Akira was very upset and might have asked the same question to the same one more than once.  
  
You may assume that n is less than 1000 and that p1 and p2 are less than 300. A line with three zeros, i.e., 0 0 0, represents the end of the input. You can assume that each data set is consistent and no contradictory answers are included.

## Sample Input

```
2 1 1
1 2 no
2 1 no
3 2 1
1 1 yes
2 2 yes
3 3 yes
2 2 1
1 2 yes
2 3 no
5 4 3
1 2 yes
1 3 no
4 5 yes
5 6 yes
6 7 no
0 0 0
```

## Sample Output

```
no
no
1
2
end
3
4
5
6
end
```

## Source

[Japan 2002 Kanazawa](http://poj.org/searchproblem?field=source&key=Japan+2002+Kanazawa)
