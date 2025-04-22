---
title: 【HDU】[5499]SDOI
type: post
slug: hdu-5499
categories:
  - hdu
ProblemParams:
    ProblemTitle: "SDOI"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "131072/131072 K"
---

## Problem Description

The Annual National Olympic of Information(NOI) will be held.The province of Shandong hold a Select(which we call SDOI for short) to choose some people to go to the NOI. $ n ( n \\leq 100 )$ people comes to the Select and there is $ m (m \\leq 50)$ people who can go to the NOI.  
  
According to the tradition and regulation.There were two rounds of the SDOI, they are so called "Round 1" and "Round 2", the full marks of each round is $300$.  
  
All the n people take part in Round1 and Round2, now the original mark of every person is known. The rule of SDOI of ranking gets to the "standard mark". For each round there is a highest original mark,let's assume that is $x$.(it is promised that not all person in one round is 0,in another way,$x > 0$). So for this round,everyone's final mark equals to his/her original $mark \* ( 300 / x )$.  
  
After we got everyone's final mark in both round.We calculate the Ultimate mark of everyone as $0.3 \* round1's$ final mark + $0.7 \* round2's$ final mark.It is so great that there were no two persons who have the same Ultimate mark.  
  
After we got everyone's Ultimate mark.We choose the persons as followed:  
  
To encourage girls to take part in the Olympic of Information.In each province,there has to be a girl in its teams.  
  
1\. If there is no girls take part in SDOI,The boys with the rank of first m enter the team.  
2\. If there is girls, then the girl who had the highest score(compared with other girls) enter the team,and other(boys and other girls) m-1 people with the highest mark enter the team.  
  
Just now all the examination had been finished.Please write a program, according to the input information of every people(Name, Sex ,The original mark of Round1 and Round2),Output the List of who can enter the team with their Ultimate mark decreasing.

## Input

There is an integer $T(T \\leq 100)$ in the first line for the number of testcases and followed $T$ testcases.  
  
For each testcase, there are two integers $n$ and $m$ in the first line$(n \\geq m)$, standing for the number of people take part in SDOI and the allowance of the team.Followed with $n$ lines,each line is an information of a person. Name(A string with length less than $20$,only contain numbers and English letters),Sex(male or female),the Original mark of Round1 and Round2 (both equal to or less than $300$) separated with a space.

## Output

For each testcase, output "The member list of Shandong team is as follows:" without Quotation marks.  
  
Followed $m$ lines,every line is the name of the team with their Ultimate mark decreasing.

## Sample Input

```
2
10 8
dxy male 230 225
davidwang male 218 235
evensgn male 150 175
tpkuangmo female 34 21
guncuye male 5 15
faebdc male 245 250
lavender female 220 216
qmqmqm male 250 245
davidlee male 240 160
dxymeizi female 205 190
2 1
dxy male 300 300
dxymeizi female 0 0
```

## Sample Output

```
The member list of Shandong team is as follows:
faebdc
qmqmqm
davidwang
dxy
lavender
dxymeizi
davidlee
evensgn
The member list of Shandong team is as follows:
dxymeizi


Hint
For the first testcase: the highest mark of Round1 if 250,so every one's mark times(300/250)=1.2, it's same to Round2.
The Final of The Ultimate score is as followed
faebdc 298.20
qmqmqm 295.80
davidwang 275.88
dxy 271.80
lavender 260.64
dxymeizi 233.40
davidlee 220.80
evensgn 201.00
tpkuangmo 29.88
guncuye 14.40

For the second testcase,There is a girl and the girl with the highest mark dxymeizi enter the team, dxy who with the highest mark,poorly,can not enter the team.
```

## Source

[BestCoder Round #59 (div.2)](https://acm.hdu.edu.cn//search.php?field=problem&key=BestCoder+Round+%2359+%28div.2%29&source=1&searchmode=source)
