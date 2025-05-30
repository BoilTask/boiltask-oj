---
title: 【HDU】[1084]What Is Your Grade?
type: post
slug: hdu-1084
categories:
  - hdu
ProblemParams:
    ProblemTitle: "What Is Your Grade?"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "65536/32768 K"
---

## Problem Description

“Point, point, life of student!”  
This is a ballad（歌谣）well known in colleges, and you must care about your score in this exam too. How many points can you get? Now, I told you the rules which are used in this course.  
There are 5 problems in this final exam. And I will give you 100 points if you can solve all 5 problems; of course, it is fairly difficulty for many of you. If you can solve 4 problems, you can also get a high score 95 or 90 (you can get the former(前者) only when your rank is in the first half of all students who solve 4 problems). Analogically（以此类推）, you can get 85、80、75、70、65、60. But you will not pass this exam if you solve nothing problem, and I will mark your score with 50.  
Note, only 1 student will get the score 95 when 3 students have solved 4 problems.  
I wish you all can pass the exam!  
Come on!

## Input

Input contains multiple test cases. Each test case contains an integer N (1<=N<=100, the number of students) in a line first, and then N lines follow. Each line contains P (0<=P<=5 number of problems that have been solved) and T（consumed time）. You can assume that all data are different when 0<p.  
A test case starting with a negative integer terminates the input and this test case should not to be processed.

## Output

Output the scores of N students in N lines for each case, and there is a blank line after each case.

## Sample Input

```
4
5 06:30:17
4 07:31:27
4 08:12:12
4 05:23:13
1
5 06:30:17
-1

```

## Sample Output

```
100
90
90
95

100

```

## Author

lcy
