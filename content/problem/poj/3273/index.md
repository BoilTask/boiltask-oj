---
title: 【POJ】[3273]Monthly Expense
type: post
slug: poj-3273
categories:
  - poj
ProblemParams:
    ProblemTitle: "Monthly Expense"
    TimeLimit: "2000MS"
    MemoryLimit: "65536K"
---

## Description

Farmer John is an astounding accounting wizard and has realized he might run out of money to run the farm. He has already calculated and recorded the exact amount of money (1 ≤ *moneyi* ≤ 10,000) that he will need to spend each day over the next *N* (1 ≤ *N* ≤ 100,000) days.

FJ wants to create a budget for a sequential set of exactly *M* (1 ≤ *M* ≤ *N*) fiscal periods called "fajomonths". Each of these fajomonths contains a set of 1 or more consecutive days. Every day is contained in exactly one fajomonth.

FJ's goal is to arrange the fajomonths so as to minimize the expenses of the fajomonth with the highest spending and thus determine his monthly spending limit.

## Input

Line 1: Two space-separated integers: *N* and *M*  
Lines 2..*N*+1: Line *i*+1 contains the number of dollars Farmer John spends on the *i*th day

## Output

Line 1: Two space-separated integers: *N* and *M*  
Lines 2..*N*+1: Line *i*+1 contains the number of dollars Farmer John spends on the *i*th day

## Sample Input

```
7 5
100
400
300
100
500
101
400
```

## Sample Output

```
500
```

## Hint

If Farmer John schedules the months so that the first two days are a month, the third and fourth are a month, and the last three are their own months, he spends at most $500 in any month. Any other method of scheduling gives a larger minimum monthly limit.

## Source

[USACO 2007 March Silver](http://poj.org/searchproblem?field=source&key=USACO+2007+March+Silver)
