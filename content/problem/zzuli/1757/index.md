---
title: 【ZZULI】[1757]Wrz and Latiao
type: post
slug: zzuli-1757
categories:
  - zzuli
ProblemParams:
  ProblemTitle: "Wrz and Latiao"
  TimeLimit: "1 Sec"
  MemoryLimit: "128 MB"
---

## 题目描述

现在，有n个柱子，每个柱子上面有一个辣条，wrz非常喜欢吃辣条，于是他想得到这些辣条，现在wrz位于第s根柱子上面，而出口在第t个柱子上面，wrz选择每次可以移动到左右两边距离为1的柱子上面，只要wrz在一根柱子上面，wrz就会立马把上面的辣条吃掉，并且在离开这个柱子后，柱子会塌陷，他不能再回到这个柱子上面。并且他必须从出口出去，必须到达出口柱子，才能被传送出去。现在wrz具有一种超能力，他可以在任何位置选择传送到第1根柱子或者第n个柱子上面，于是问题来了，wrz想要吃掉所有的辣条，他最少需要使用几次超能力？

## 输入

多组数据（到文件尾结束），每组数据给你一个整数n(n<=20)表示有n根柱子，一个整数s（1<=s<=n）表示wrz起始在第s根柱子上面，一个整数t（1<=t<=n）表示出口在第t根柱子上面。

## 输出

输出每组数据wrz把所有辣条吃掉并且从出口出去使用超能力的最少次数，如果他不能得到所有的辣条并且出去，输出-1，每组一行。

## 样例输入

```
4 1 4
4 1 3
```

## 样例输出

```
0
1
```

## 来源/分类

[戴姆勒](https://web.archive.org/web/http://acm.zzuli.edu.cn/problemset.php?search=%E6%88%B4%E5%A7%86%E5%8B%92)
