---
title: 【HDU】[1872]稳定排序
type: post
slug: hdu-1872
categories:
  - hdu
ProblemParams:
    ProblemTitle: "稳定排序"
    TimeLimit: "3000/1000 MS"
    MemoryLimit: "32768/32768 K"
---

## Problem Description

大家都知道，快速排序是不稳定的排序方法。  
如果对于数组中出现的任意a\[i\],a\[j\](i<j),其中a\[i\]==a\[j\]，在进行排序以后a\[i\]一定出现在a\[j\]之前，则认为该排序是稳定的。  
  
某高校招生办得到一份成绩列表，上面记录了考生名字和考生成绩。并且对其使用了某排序算法按成绩进行递减排序。现在请你判断一下该排序算法是否正确，如果正确的话，则判断该排序算法是否为稳定的。

## Input

本题目包含多组输入，请处理到文件结束。  
对于每组数据，第一行有一个正整数N(0<N<300)，代表成绩列表中的考生数目。  
接下来有N行，每一行有一个字符串代表考生名字(长度不超过50，仅包含'a'~'z'),和一个整数代表考生分数(小于500)。其中名字和成绩用一个空格隔开。  
再接下来又有N行，是上述列表经过某排序算法以后生成的一个序列。格式同上。

## Output

对于每组数据，如果算法是正确并且稳定的，就在一行里面输出"Right"。如果算法是正确的但不是稳定的，就在一行里面输出"Not Stable"，并且在下面输出正确稳定排序的列表，格式同输入。如果该算法是错误的，就在一行里面输出"Error",并且在下面输出正确稳定排序的列表，格式同输入。  
  
注意，本题目不考虑该排序算法是错误的，但结果是正确的这样的意外情况。

## Sample Input

```
3
aa 10
bb 10
cc 20
cc 20
bb 10
aa 10
3
aa 10
bb 10
cc 20
cc 20
aa 10
bb 10
3
aa 10
bb 10
cc 20
aa 10
bb 10
cc 20
```

## Sample Output

```
Not Stable
cc 20
aa 10
bb 10
Right
Error
cc 20
aa 10
bb 10
```

## Author

linle

## Source

[2008浙大研究生复试热身赛（2）——全真模拟](https://acm.hdu.edu.cn//search.php?field=problem&key=2008%D5%E3%B4%F3%D1%D0%BE%BF%C9%FA%B8%B4%CA%D4%C8%C8%C9%ED%C8%FC%A3%A82%A3%A9%A1%AA%A1%AA%C8%AB%D5%E6%C4%A3%C4%E2&source=1&searchmode=source)
