---
title: 【POJ】[1586]QS Network
type: post
slug: zoj-1586
categories:
  - zoj
ProblemParams:
    ProblemTitle: "QS Network"
    TimeLimit: "2000 ms"
    MemoryLimit: "65536 KB"
---

Sunny Cup 2003 - Preliminary Round
----------------------------------

April 20th, 12:00 - 17:00

### Problem E: QS Network

  
In the planet w-503 of galaxy cgb, there is a kind of intelligent creature named QS. QScommunicate with each other via networks. If two QS want to get connected, they need to buy two network adapters (one for each QS) and a segment of network cable. Please be advised that ONE NETWORK ADAPTER CAN ONLY BE USED IN A SINGLE CONNECTION.(ie. if a QS want to setup four connections, it needs to buy four adapters). In the procedure of communication, a QS broadcasts its message to all the QS it is connected with, the group of QS who receive the message broadcast the message to all the QS they connected with, the procedure repeats until all the QS's have received the message.

A sample is shown below:

![](https://images.ptausercontent.com/0000%2F1586%2F1586.gif)

  
A sample QS network, and QS A want to send a message.  
  
Step 1. QS A sends message to QS B and QS C;  
  
Step 2. QS B sends message to QS A ; QS C sends message to QS A and QS D;  
  
Step 3. the procedure terminates because all the QS received the message.

Each QS has its favorate brand of network adapters and always buys the brand in all of its connections. Also the distance between QS vary. Given the price of each QS's favorate brand of network adapters and the price of cable between each pair of QS, your task is to write a program to determine the minimum cost to setup a QS network.

  
**Input**

The 1st line of the input contains an integer t which indicates the number of data sets.  
  
From the second line there are t data sets.  
  
In a single data set,the 1st line contains an interger n which indicates the number of QS.  
  
The 2nd line contains n integers, indicating the price of each QS's favorate network adapter.  
  
In the 3rd line to the n+2th line contain a matrix indicating the price of cable between ecah pair of QS.

Constrains:

all the integers in the input are non-negative and not more than 1000.

  
**Output**

for each data set,output the minimum cost in a line. NO extra empty lines needed.

  
**Sample Input**

1  
3  
10 20 30  
0 100 200  
100 0 300  
200 300 0

  
**Sample Output**

370

## 作者

JIANG, Jiefeng
