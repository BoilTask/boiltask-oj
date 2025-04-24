---
title: 【NYOJ】[1025]A Famous Music Composer
type: post
slug: nyoj-1025
categories:
  - nyoj
ProblemParams:
  ProblemTitle: "A Famous Music Composer"
  TimeLimit: ""
  MemoryLimit: ""
---

## 题目描述

Mr. B is a famous music composer. One of his most famous work was his set of preludes. These 24 pieces span the 24 musical keys (there are musically distinct 12 scale notes, and each may use major or minor tonality). The 12 distinct scale notes are: 

<table style="width:100%;" cellpadding="2" cellspacing="0" border="1" bordercolor="#000000" align="center"><tbody><tr><td><b>&nbsp;A &nbsp; &nbsp;</b></td><td><b>A#=Bb&nbsp;</b></td><td><b>B &nbsp; &nbsp; &nbsp;</b></td><td><b>&nbsp;C &nbsp; &nbsp;&nbsp;</b></td><td><b>&nbsp;C#=Db</b></td><td><b>D &nbsp; &nbsp; &nbsp;</b></td><td><b>D#=Eb&nbsp;</b></td><td><b>E &nbsp; &nbsp; &nbsp;</b></td><td><b>F &nbsp; &nbsp; &nbsp;</b></td><td><b>&nbsp;F#=Gb</b></td><td><b>&nbsp;G &nbsp; &nbsp;&nbsp;</b></td><td><b>&nbsp;G#=Ab</b></td></tr></tbody></table>

  

Five of the notes have two alternate names, as is indicated above with equals sign. Thus, there are 17 possible names of scale notes, but only 12 musically distinct notes. When using one of these as the keynote for a musical key, we can further distinguish between major and minor tonalities. This gives 34 possible keys, of which 24 are musically distinct. 

In naming his preludes, Mr. B used all the keys except the following 10, which were named instead by their alternate names: 

<table style="width:100%;" cellpadding="2" cellspacing="0" border="1" bordercolor="#000000"><tbody><tr><td><b>&nbsp;Ab minor</b></td><td><b>&nbsp;A# major</b></td><td><b>A# minor&nbsp;</b></td><td><b>C# major&nbsp;</b></td><td><b>Db minor</b></td></tr><tr><td><b>&nbsp;D# major</b></td><td><b>&nbsp;D# minor</b></td><td><b>Gb major&nbsp;</b></td><td><b>Gb minor&nbsp;</b></td><td><b>G# major&nbsp;</b></td></tr></tbody></table>

Write a program that, given the name of a key, give an alternate name if it has one, or report the key name is unique.

## 输入描述

Each test case is described by one line having the format "note tonality", where "note" is one of the 17 names for the scale notes given above, and "tonality" is either "major" or "minor" (quotes for clarify).

## 输出描述

For each case output the required answer, following the format of the sample.

## 用例

### 用例输入

```
Ab minor
D# major
G minor
```  

### 用例输出

```
Case 1: G# minor
Case 2: Eb major
Case 3: UNIQUE
```

## 作者

DYM\_

## 来源

NYOJ
