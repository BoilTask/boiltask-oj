---
title: 【HDU】[1509]Windows Message Queue
type: post
slug: hdu-1509
categories:
  - hdu
ProblemParams:
    ProblemTitle: "Windows Message Queue"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "65536/32768 K"
---

## Problem Description

Message queue is the basic fundamental of windows system. For each process, the system maintains a message queue. If something happens to this process, such as mouse click, text change, the system will add a message to the queue. Meanwhile, the process will do a loop for getting message from the queue according to the priority value if it is not empty. Note that the less priority value means the higher priority. In this problem, you are asked to simulate the message queue for putting messages to and getting message from the message queue.

## Input

There's only one test case in the input. Each line is a command, "GET" or "PUT", which means getting message or putting message. If the command is "PUT", there're one string means the message name and two integer means the parameter and priority followed by. There will be at most 60000 command. Note that one message can appear twice or more and if two messages have the same priority, the one comes first will be processed first.(i.e., FIFO for the same priority.) Process to the end-of-file.

## Output

For each "GET" command, output the command getting from the message queue with the name and parameter in one line. If there's no message in the queue, output "EMPTY QUEUE!". There's no output for "PUT" command.

## Sample Input

```
GET
PUT msg1 10 5
PUT msg2 10 4
GET
GET
GET

```

## Sample Output

```
EMPTY QUEUE!
msg2 10
msg1 10
EMPTY QUEUE!

```

## Author

ZHOU, Ran

## Source

[Zhejiang University Local Contest 2006, Preliminary](https://acm.hdu.edu.cn//search.php?field=problem&key=Zhejiang+University+Local+Contest+2006%2C+Preliminary&source=1&searchmode=source)
