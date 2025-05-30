---
title: 【HDU】[1863]畅通工程
type: post
slug: hdu-1863
categories:
  - hdu
ProblemParams:
    ProblemTitle: "畅通工程"
    TimeLimit: "1000/1000 MS"
    MemoryLimit: "32768/32768 K"
---

## Problem Description

省政府“畅通工程”的目标是使全省任何两个村庄间都可以实现公路交通（但不一定有直接的公路相连，只要能间接通过公路可达即可）。经过调查评估，得到的统计表中列出了有可能建设公路的若干条道路的成本。现请你编写程序，计算出全省畅通需要的最低成本。

## Input

测试输入包含若干测试用例。每个测试用例的第1行给出评估的道路条数 N、村庄数目M ( < 100 )；随后的 N  
行对应村庄间道路的成本，每行给出一对正整数，分别是两个村庄的编号，以及此两村庄间道路的成本（也是正整数）。为简单起见，村庄从1到M编号。当N为0时，全部输入结束，相应的结果不要输出。

## Output

对每个测试用例，在1行里输出全省畅通需要的最低成本。若统计数据不足以保证畅通，则输出“?”。

## Sample Input

```
3 3
1 2 1
1 3 2
2 3 4
1 3
2 3 2
0 100
```

## Sample Output

```
3
?

```

## Source

[浙大计算机研究生复试上机考试-2007年](https://acm.hdu.edu.cn//search.php?field=problem&key=%D5%E3%B4%F3%BC%C6%CB%E3%BB%FA%D1%D0%BE%BF%C9%FA%B8%B4%CA%D4%C9%CF%BB%FA%BF%BC%CA%D4-2007%C4%EA&source=1&searchmode=source)
