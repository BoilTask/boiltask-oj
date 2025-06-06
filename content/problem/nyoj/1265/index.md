---
title: 【NYOJ】[1265]字符串逆序输出
type: post
slug: nyoj-1265
categories:
  - nyoj
ProblemParams:
  ProblemTitle: "字符串逆序输出"
  TimeLimit: "3000 MS"
  MemoryLimit: "256 MB"
---

## 题目描述

给定一行字符，逆序输出此行（空格.数字不输出）

## 输入描述

第一行是一个整数N(N<10)表示测试数据的组数）  
每组测试数据占一行，每行数据中间有且只有一个空格（这样你可以把此行当成两个字符串读取）。  
每行字符长度不超过40  
并且保证输入的字符只有空格（1个），数字，小写字母三种

## 输出描述

对应每行测试数据，逆序输出（空格和数字不输出）

## 用例

### 用例输入

```
3
abc 123de
abc 123
abc d
```
  

### 用例输出

```
edcba
cba
dcba
```

## 作者

ACM\_赵铭浩

## 来源

NYOJ
