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

<h2 align="center">Sunny Cup 2003 - Preliminary Round</h2>
<p align="center">April 20th, 12:00 - 17:00 </p>
<h3 align="center">Problem E: QS Network</h3>
<p><br>
  In the planet w-503 of galaxy cgb, there is a kind of intelligent creature named 
  QS. QScommunicate with each other via networks. If two QS want to get connected, 
  they need to buy two network adapters (one for each QS) and a segment of network 
  cable. Please be advised that ONE NETWORK ADAPTER CAN ONLY BE USED IN A SINGLE 
  CONNECTION.(ie. if a QS want to setup four connections, it needs to buy four 
  adapters). In the procedure of communication, a QS broadcasts its message to 
  all the QS it is connected with, the group of QS who receive the message broadcast 
  the message to all the QS they connected with, the procedure repeats until all 
  the QS's have received the message.</p>
<p>A sample is shown below:</p>
<p align="center"><img src="https://images.ptausercontent.com/0000%2F1586%2F1586.gif" width="232" height="197"></p>
<p></p>
<p><br>
  A sample QS network, and QS A want to send a message.<br>
  <br>
  Step 1. QS A sends message to QS B and QS C;<br>
  <br>
  Step 2. QS B sends message to QS A ; QS C sends message to QS A and QS D;<br>
  <br>
  Step 3. the procedure terminates because all the QS received the message.</p>
<p> Each QS has its favorate brand of network adapters and always buys the brand 
  in all of its connections. Also the distance between QS vary. Given the price 
  of each QS's favorate brand of network adapters and the price of cable between 
  each pair of QS, your task is to write a program to determine the minimum cost 
  to setup a QS network.</p>
<p><br>
  <b>Input</b></p>
<p>The 1st line of the input contains an integer t which indicates the number 
  of data sets.<br>
  <br>
  From the second line there are t data sets.<br>
  <br>
  In a single data set,the 1st line contains an interger n which indicates the 
  number of QS.<br>
  <br>
  The 2nd line contains n integers, indicating the price of each QS's favorate 
  network adapter.<br>
  <br>
  In the 3rd line to the n+2th line contain a matrix indicating the price of cable 
  between ecah pair of QS.</p>
<p>Constrains:</p>
<p>all the integers in the input are non-negative and not more than 1000.</p>
<p></p>
<p><br>
  <b>Output</b></p>
<p>for each data set,output the minimum cost in a line. NO extra empty lines needed.</p>
<p><br>
  <b>Sample Input</b></p>
<p>1<br>
  3<br>
  10 20 30<br>
  0 100 200<br>
  100 0 300<br>
  200 300 0</p>
<p><br>
  <b>Sample Output</b></p>
<p>370<br>
</p>
<p><br>
</p>


## 作者

JIANG, Jiefeng
