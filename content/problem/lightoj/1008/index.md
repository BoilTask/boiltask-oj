---
title: 【LightOJ】[1008]Fibsieve's Fantabulous Birthday
type: post
slug: lightoj-1008
categories:
  - lightoj
ProblemParams:
    ProblemTitle: "Fibsieve's Fantabulous Birthday"
    TimeLimit: "1 seconds"
    MemoryLimit: "64 MB"
---

## Description

Fibsieve had a fantabulous (yes, it's an actual word) birthday party this year. He had so many gifts that he was actually thinking of not having a party next year. Among these gifts there was an **N x N** glass chessboard that had a light in each of its cells. When the board was turned on a distinct cell would light up every second, and then go dark.

The cells would light up in the sequence shown in the diagram. Each cell is marked with the second in which it would light up.

|  |  |  |  |  |
| --- | --- | --- | --- | --- |
| 25 | 24 | 23 | 22 | 21 |
| 10 | 11 | 12 | 13 | 20 |
| 9 | 8 | 7 | 14 | 19 |
| 2 | 3 | 6 | 15 | 18 |
| 1 | 4 | 5 | 16 | 17 |

In the first second the light at cell (1, 1) would be on. And in the 5th second the cell (3, 1) would be on. Now, Fibsieve is trying to predict which cell will light up at a certain time (given in seconds). Assume that **N** is large enough.

## Input

Input starts with an integer **T (≤ 200)**, denoting the number of test cases.

Each case will contain an integer **S (1 ≤ S ≤ 1015)** which stands for the time.

## Output

For each case you have to print the case number and two numbers **(x, y)**, the column and the row number.

## Sample Input

```
3
8
20
25

```

## Sample Output

```
Case 1: 2 3
Case 2: 5 4
Case 3: 1 5

```

## Notes

LOJ 1008 - Fibsieve's Fantabulous Birthday
==========================================

---

In the first input, we will be given the number of test cases _T_ . After that we will be given an input _S_ upto _T_ times, each of which represents the S-th second and we have to output which cell would light up by outputting the value of its column and row number separated by a single space.

If we take few examples from the chess board, for 25, its row number is 5 and 5 = √25. For 24, its row number is 5 and 5 = ⌈√24⌉. However, for 16, its column number is 4 and 4 = ⌈√16⌉. Similarly, for 15, its column number is 4 and 4 = ⌈√15⌉. So, if ⌈√S⌉ is an even number, the ceiling value of the square root of _S_ produces the column number and if it is an odd number, it produces the row number.

For the column number of 24 it is 2 and here 2 = (closest square number to 24 ~ 24) + 1 = 25 - 24 + 1 = 2. In case of 15, its row number is 2 and 2 = (closest square number to 15 ~ 15) + 1 = 16 -15 + 1 = 2. In case of both 24 and 15, the closest square number is after them.

But in case of 17, its column number is 5 and 5 = ⌈√17⌉ although here ⌈√17⌉ produced 5 which is an odd number and again the row number is 1 = (closest square number to 17 ~ 17) = 17 - 16 = 1. Now to determine whether the closest square number to _S_ is after or before it, we can determine by whether ⌈√S⌉² - _S_ > ⌈√S⌉ or not. If it is lesser than it then we know that the closest square number to _S_ is before _S_ and if it is greater then we know that the closest square number to _S_ is after _S_. If we examine the closest square number to _S_ when it is after _S_, that number is actually (⌈√S⌉ - 1)². Example: for 17, (⌈√17⌉ - 1)² = (5 - 1)² = 16 and from that, 17 - 16 = 1 which is the row number of 17.

The above implementation is `Accepted`.

Solution in C
-------------

```c
#include <stdio.h>
#include <math.h>

int main()
{
    int cases;
    scanf("%d", &cases);
    for (int i = 1; i <= cases; i++)
    {
        long long seconds, root, lackings, row, column;
        scanf("%lld", &seconds);
        root = ceil(sqrt(seconds * 1.0));
        lackings = root * root - seconds;
        if (lackings < root){
            row = root;
            column = lackings + 1;
        }
        else{
            column = root;
            row = seconds - (root-1) * (root-1);
        }
        if(root % 2 == 0){
            long long temp = column;
            column = row;
            row = temp;
        }
        printf("Case %d: %lld %lld\n",i, column, row);
    }

    return 0;
}
```

---

[Tutorial source](https://github.com/lightoj-dev/problem-tutorials/blob/main/1008/en.md "null")
