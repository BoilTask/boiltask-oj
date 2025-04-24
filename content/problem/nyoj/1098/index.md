---
title: 【NYOJ】[1098]成绩转换
type: post
slug: nyoj-1098
categories:
  - nyoj
ProblemParams:
  ProblemTitle: "成绩转换"
  TimeLimit: "3000 MS"
  MemoryLimit: "256 MB"
---

## 题目描述

输入一个百分制的成绩M，将其转换成对应的等级，具体转换规则如下：  
90~100为A;  
80~89为B;  
70~79为C;  
60~69为D;  
0~59为E;

## 输入描述

第一行是一个整数N，表示测试数据的组数(N<10)  
每组测试数据占一行，由一个整数M组成(0<=M<=100)。

## 输出描述

对于每组输入数据，输出一行。

## 用例

### 用例输入

```
2
97
80
```  

### 用例输出

```
A
B
```

## 提示

\`\`\` //多组输入 #include int main() { int t; scanf("%d",&t); while(t--) { //代码块 } return 0; } \`\`\`

## 作者

张云聪

## 来源

NYOJ
