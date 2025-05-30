---
title: 【POJ】[1466]Girls and Boys
type: post
slug: poj-1466
categories:
  - poj
ProblemParams:
    ProblemTitle: "Girls and Boys"
    TimeLimit: "5000MS"
    MemoryLimit: "10000K"
---

## Description

In the second year of the university somebody started a study on the romantic relations between the students. The relation "romantically involved" is defined between one girl and one boy. For the study reasons it is necessary to find out the maximum set satisfying the condition: there are no two students in the set who have been "romantically involved". The result of the program is the number of students in such a set.

## Input

The input contains several data sets in text format. Each data set represents one set of subjects of the study, with the following description:  
  
the number of students  
the description of each student, in the following format  
student\_identifier:(number\_of\_romantic\_relations) student\_identifier1 student\_identifier2 student\_identifier3 ...  
or  
student\_identifier:(0)  
  
The student\_identifier is an integer number between 0 and n-1 (n <=500 ), for n subjects.

## Output

The input contains several data sets in text format. Each data set represents one set of subjects of the study, with the following description:  
  
the number of students  
the description of each student, in the following format  
student\_identifier:(number\_of\_romantic\_relations) student\_identifier1 student\_identifier2 student\_identifier3 ...  
or  
student\_identifier:(0)  
  
The student\_identifier is an integer number between 0 and n-1 (n <=500 ), for n subjects.

## Sample Input

```
7
0: (3) 4 5 6
1: (2) 4 6
2: (0)
3: (0)
4: (2) 0 1
5: (1) 0
6: (2) 0 1
3
0: (2) 1 2
1: (1) 0
2: (1) 0
```

## Sample Output

```
5
2
```

## Source

[Southeastern Europe 2000](http://poj.org/searchproblem?field=source&key=Southeastern+Europe+2000)
