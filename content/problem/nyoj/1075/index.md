---
title: 【NYOJ】[1075]日期计算
type: post
slug: nyoj-1075
categories:
  - nyoj
ProblemParams:
  ProblemTitle: "日期计算"
  TimeLimit: "3000 MS"
  MemoryLimit: "256 MB"
---

## 题目描述

如题，输入一个日期，格式如：2010 10 24 ，判断这一天是这一年中的第几天。

## 输入描述

第一行输入一个数N（0<N<=100）,表示有N组测试数据。后面的N行输入多组输入数据，每行的输入数据都是一个按题目要求格式输入的日期。

## 输出描述

每组输入数据的输出占一行，输出判断出的天数n

## 用例

### 用例输入

```
3
2000 4 5
2001 5 4
2010 10 24
```  

### 用例输出

```
96
124
297
```

## 提示

\`\`\` //多组输入 #include int main() { int t; scanf("%d",&t); while(t--) { //代码块 } return 0; } \`\`\`

## 作者

naonao

## 来源

NYOJ
