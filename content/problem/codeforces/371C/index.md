---
title: 【Codeforces】[371C]Hamburgers
type: post
slug: codeforces-371C
categories:
  - codeforces
ProblemParams:
    ProblemTitle: "Hamburgers"
    TimeLimit: "1 second"
    MemoryLimit: "256 megabytes"
---

## Description

Polycarpus loves hamburgers very much. He especially adores the hamburgers he makes with his own hands. Polycarpus thinks that there are only three decent ingredients to make hamburgers from: a bread, sausage and cheese. He writes down the recipe of his favorite "Le Hamburger de Polycarpus" as a string of letters 'B' (bread), 'S' (sausage) и 'C' (cheese). The ingredients in the recipe go from bottom to top, for example, recipe "ВSCBS" represents the hamburger where the ingredients go from bottom to top as bread, sausage, cheese, bread and sausage again.

Polycarpus has $n_{b}$ pieces of bread, $n_{s}$ pieces of sausage and $n_{c}$ pieces of cheese in the kitchen. Besides, the shop nearby has all three ingredients, the prices are $p_{b}$ rubles for a piece of bread, $p_{s}$ for a piece of sausage and $p_{c}$ for a piece of cheese.

Polycarpus has $r$ rubles and he is ready to shop on them. What maximum number of hamburgers can he cook? You can assume that Polycarpus cannot break or slice any of the pieces of bread, sausage or cheese. Besides, the shop has an unlimited number of pieces of each ingredient.

## Input

The first line of the input contains a non-empty string that describes the recipe of "Le Hamburger de Polycarpus". The length of the string doesn't exceed 100, the string contains only letters 'B' (uppercase English B), 'S' (uppercase English S) and 'C' (uppercase English C).

The second line contains three integers $n_{b}$, $n_{s}$, $n_{c}$ ($1 ≤ n_{b}, n_{s}, n_{c} ≤ 100$) — the number of the pieces of bread, sausage and cheese on Polycarpus' kitchen. The third line contains three integers $p_{b}$, $p_{s}$, $p_{c}$ ($1 ≤ p_{b}, p_{s}, p_{c} ≤ 100$) — the price of one piece of bread, sausage and cheese in the shop. Finally, the fourth line contains integer $r$ ($1 ≤ r ≤ 10^{12}$) — the number of rubles Polycarpus has.

Please, do not write the %lld specifier to read or write 64-bit integers in С++. It is preferred to use the cin, cout streams or the %I64d specifier.

## Output

Print the maximum number of hamburgers Polycarpus can make. If he can't make any hamburger, print 0.

## Examples

### Input

```
BBBSSC
6 4 1
1 2 3
4

```

### Output

```
2

```

### Input

```
BBC
1 10 1
1 10 1
21

```

### Output

```
7

```

### Input

```
BSC
1 1 1
1 1 3
1000000000000

```

### Output

```
200000000001

```
