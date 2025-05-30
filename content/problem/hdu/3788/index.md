---
title: 【HDU】[3788]ZOJ问题
type: post
slug: hdu-3788
categories:
  - hdu
ProblemParams:
    ProblemTitle: "ZOJ问题"
    TimeLimit: "2000/1000 MS"
    MemoryLimit: "32768/32768 K"
---

## Problem Description

对给定的字符串(只包含'z','o','j'三种字符),判断他是否能AC。  
  
是否AC的规则如下：  
1\. zoj能AC；  
2\. 若字符串形式为xzojx，则也能AC，其中x可以是N个'o' 或者为空；  
3\. 若azbjc 能AC，则azbojac也能AC，其中a,b,c为N个'o'或者为空；

## Input

输入包含多组测试用例，每行有一个只包含'z','o','j'三种字符的字符串，字符串长度小于等于1000；

## Output

对于给定的字符串，如果能AC则请输出字符串“Accepted”，否则请输出“Wrong Answer”。

## Sample Input

```
zoj
ozojo
ozoojoo
oozoojoooo
zooj
ozojo
oooozojo
zojoooo

```

## Sample Output

```
Accepted
Accepted
Accepted
Accepted
Accepted
Accepted
Wrong Answer
Wrong Answer
```

## Source

[浙大计算机研究生复试上机考试-2010年](https://acm.hdu.edu.cn//search.php?field=problem&key=%D5%E3%B4%F3%BC%C6%CB%E3%BB%FA%D1%D0%BE%BF%C9%FA%B8%B4%CA%D4%C9%CF%BB%FA%BF%BC%CA%D4-2010%C4%EA&source=1&searchmode=source)
