---
title: 【HDU】[1875]畅通工程再续
type: post
slug: hdu-1875
categories:
  - hdu
ProblemParams:
    ProblemTitle: "畅通工程再续"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "32768/32768 K"
---

## Problem Description

相信大家都听说一个“百岛湖”的地方吧，百岛湖的居民生活在不同的小岛中，当他们想去其他的小岛时都要通过划小船来实现。现在政府决定大力发展百岛湖，发展首先要解决的问题当然是交通问题，政府决定实现百岛湖的全畅通！经过考察小组RPRush对百岛湖的情况充分了解后，决定在符合条件的小岛间建上桥，所谓符合条件，就是2个小岛之间的距离不能小于10米，也不能大于1000米。当然，为了节省资金，只要求实现任意2个小岛之间有路通即可。其中桥的价格为 100元/米。

## Input

输入包括多组数据。输入首先包括一个整数T(T <= 200)，代表有T组数据。  
每组数据首先是一个整数C(C <= 100),代表小岛的个数，接下来是C组坐标，代表每个小岛的坐标，这些坐标都是 0 <= x, y <= 1000的整数。

## Output

每组输入数据输出一行，代表建桥的最小花费，结果保留一位小数。如果无法实现工程以达到全部畅通，输出”oh!”.

## Sample Input

```
2
2
10 10
20 20
3
1 1
2 2
1000 1000

```

## Sample Output

```
1414.2
oh!

```

## Author

8600

## Source

[2008浙大研究生复试热身赛（2）——全真模拟](https://acm.hdu.edu.cn//search.php?field=problem&key=2008%D5%E3%B4%F3%D1%D0%BE%BF%C9%FA%B8%B4%CA%D4%C8%C8%C9%ED%C8%FC%A3%A82%A3%A9%A1%AA%A1%AA%C8%AB%D5%E6%C4%A3%C4%E2&source=1&searchmode=source)
