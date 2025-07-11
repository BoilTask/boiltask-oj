---
title: 【ZZULI】[1804]ZY学长的密码
type: post
slug: zzuli-1804
categories:
  - zzuli
ProblemParams:
  ProblemTitle: "ZY学长的密码"
  TimeLimit: "1 Sec"
  MemoryLimit: "128 MB"
---

## 题目描述

zy比较粗心大意，经常忘记一些帐号的密码。  
这不他的校园卡密码又给忘记了，但是他依稀记得关于密码的一些字符。  
例如zy能够记得的校园卡密码是“zsdf\*\*dafs\*\*”，其中“\*"位置代表的字符是他忘记的。  
现在下面有n组密码，有多少组可能是zy密码，你能帮助他吗？不然他都吃不上饭了。（假如zy的密码是“abc\*”，则“abcf”可能是他的密码,“abcd”也可能是他的密码。）

## 输入

第一行为数字T（1<=T<=100)，表示有T组测试数据。  
每组测试数据第一行为一串字符，表示zy能够记得的密码（密码可能包含空格，标点符号，长度不超过100，但无其他特殊字符）。  
第二行为数字n(1<=n<=100)，表示有n个密码，随后n行，每行有一串字符，表示一个密码。

## 输出

输出n个密码中可能是zy的密码的个数。

## 样例输入

```
2
abc*
3
abca
abcde
ab
abcd*fs*
3
abcd fsa
abcdsfsb
abcdfs
```

## 样例输出

```
1
2
```

## 来源/分类

[](https://web.archive.org/web/http://acm.zzuli.edu.cn/problemset.php?search=)
