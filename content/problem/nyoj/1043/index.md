---
title: 【NYOJ】[1043]24 Point game
type: post
slug: nyoj-1043
categories:
  - nyoj
---

# 24 Point game

## 题目描述

There is a game which is called 24 Point game.

In this game , you will be given some numbers. Your task is to find an expression which have all the given numbers and the value of the expression should be 24 .The expression mustn't have any other operator except plus,minus,multiply,divide and the brackets. 

e.g. If the numbers you are given is "3 3 8 8", you can give "8/(3-8/3)" as an answer. All the numbers should be used and the bracktes can be nested. 

Your task in this problem is only to judge whether the given numbers can be used to find a expression whose value is the given number。

## 输入描述

The input has multicases and each case contains one line The first line of the input is an non-negative integer C(C<=100),which indicates the number of the cases. Each line has some integers,the first integer M(0<=M<=5) is the total number of the given numbers to consist the expression,the second integers N(0<=N<=100) is the number which the value of the expression should be. Then,the followed M integer is the given numbers. All the given numbers is non-negative and less than 100

## 输出描述

For each test-cases,output "Yes" if there is an expression which fit all the demands,otherwise output "No" instead.

## 示例

2 4 24 3 3 8 8 3 24 8 3 3

Yes No

## 提示

无

## 来源

NYOJ
