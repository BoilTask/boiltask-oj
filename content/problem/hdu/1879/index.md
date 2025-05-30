---
title: 【HDU】[1879]继续畅通工程
type: post
slug: hdu-1879
categories:
  - hdu
ProblemParams:
    ProblemTitle: "继续畅通工程"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "32768/32768 K"
---

## Problem Description

省政府“畅通工程”的目标是使全省任何两个村庄间都可以实现公路交通（但不一定有直接的公路相连，只要能间接通过公路可达即可）。现得到城镇道路统计表，表中列出了任意两城镇间修建道路的费用，以及该道路是否已经修通的状态。现请你编写程序，计算出全省畅通需要的最低成本。

## Input

测试输入包含若干测试用例。每个测试用例的第1行给出村庄数目N ( 1< N < 100 )；随后的 N(N-1)/2 行对应村庄间道路的成本及修建状态，每行给4个正整数，分别是两个村庄的编号（从1编号到N），此两村庄间道路的成本，以及修建状态：1表示已建，0表示未建。  
  
当N为0时输入结束。

## Output

每个测试用例的输出占一行，输出全省畅通需要的最低成本。

## Sample Input

```
3
1 2 1 0
1 3 2 0
2 3 4 0
3
1 2 1 0
1 3 2 0
2 3 4 1
3
1 2 1 0
1 3 2 1
2 3 4 1
0
```

## Sample Output

```
3
1
0
```

## Author

ZJU

## Source

[浙大计算机研究生复试上机考试-2008年](https://acm.hdu.edu.cn//search.php?field=problem&key=%D5%E3%B4%F3%BC%C6%CB%E3%BB%FA%D1%D0%BE%BF%C9%FA%B8%B4%CA%D4%C9%CF%BB%FA%BF%BC%CA%D4-2008%C4%EA&source=1&searchmode=source)
