---
title: 【LightOJ】[1213]Fantasy of a Summation
type: post
slug: lightoj-1213
categories:
  - lightoj
ProblemParams:
    ProblemTitle: "Fantasy of a Summation"
    TimeLimit: "1 seconds"
    MemoryLimit: "64 MB"
---

## Description

If you think codes, eat codes then sometimes you may get stressed. In your dreams you may see huge codes, as I have seen once. Here is the code I saw in my dream.

```cpp
#include &lt;stdio.h&gt;

int cases, caseno;
int n, K, MOD;
int A[1001];

int main() {
    scanf("%d", &amp;cases);
    while( cases-- ) {
        scanf("%d %d %d", &amp;n, &amp;K, &amp;MOD);
        int i, i1, i2, i3, ... , iK;
        for( i = 0; i &lt; n; i++ ) scanf("%d", &amp;A[i]);

        int res = 0;
        for( i1 = 0; i1 &lt; n; i1++ ) {
            for( i2 = 0; i2 &lt; n; i2++ ) {
                for( i3 = 0; i3 &lt; n; i3++ ) {
                    ...
                    for( iK = 0; iK &lt; n; iK++ ) {
                        res = ( res + A[i1] + A[i2] + ... + A[iK] ) % MOD;
                    }
                    ...
                }
            }
        }
        printf("Case %d: %d\n", ++caseno, res);
    }
    return 0;
}
```

Actually the code was about: 'You are given three integers **n**, **K**, **MOD** and **n** integers: **A0, A1, A2 ... An-1**, you have to write **K** nested loops and calculate the summation of all **Ai** where **i** is the value of any nested loop variable.'

## Input

Input starts with an integer **T (≤ 100)**, denoting the number of test cases.

Each case starts with three integers: **n (1 ≤ n ≤ 1000), K (1 ≤ K < 231), MOD (1 ≤ MOD ≤ 35000)**. The next line contains **n** non-negative integers denoting **A0, A1, A2 ... An-1**. Each of these integers will be fit into a 32 bit signed integer.

## Output

For each case, print the case number and result of the code.

## Sample Input

```
2
3 1 35000
1 2 3
2 3 35000
1 2

```

## Sample Output

```
Case 1: 6
Case 2: 36

```
