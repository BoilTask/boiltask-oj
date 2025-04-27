---
title: 【POJ】[2585]Window Pains
type: post
slug: poj-2585
categories:
  - poj
ProblemParams:
    ProblemTitle: "Window Pains"
    TimeLimit: "1000MS"
    MemoryLimit: "65536K"
---

## Description

Boudreaux likes to multitask, especially when it comes to using his computer. Never satisfied with just running one application at a time, he usually runs nine applications, each in its own window. Due to limited screen real estate, he overlaps these windows and brings whatever window he currently needs to work with to the foreground. If his screen were a 4 x 4 grid of squares, each of Boudreaux's windows would be represented by the following 2 x 2 windows:  

<table width="80%"><tbody><tr><td><table cellpadding="4" border="1"><tbody><tr><td><tt>1</tt></td><td><tt>1</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr><tr><td><tt>1</tt></td><td><tt>1</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr></tbody></table></td><td><table cellpadding="4" border="1"><tbody><tr><td><tt>.</tt></td><td><tt>2</tt></td><td><tt>2</tt></td><td><tt>.</tt></td></tr><tr><td><tt>.</tt></td><td><tt>2</tt></td><td><tt>2</tt></td><td><tt>.</tt></td></tr><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr></tbody></table></td><td><table cellpadding="4" border="1"><tbody><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>3</tt></td><td><tt>3</tt></td></tr><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>3</tt></td><td><tt>3</tt></td></tr><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr></tbody></table></td></tr><tr><td><table cellpadding="4" border="1"><tbody><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr><tr><td><tt>4</tt></td><td><tt>4</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr><tr><td><tt>4</tt></td><td><tt>4</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr></tbody></table></td><td><table cellpadding="4" border="1"><tbody><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr><tr><td><tt>.</tt></td><td><tt>5</tt></td><td><tt>5</tt></td><td><tt>.</tt></td></tr><tr><td><tt>.</tt></td><td><tt>5</tt></td><td><tt>5</tt></td><td><tt>.</tt></td></tr><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr></tbody></table></td><td><table cellpadding="4" border="1"><tbody><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>6</tt></td><td><tt>6</tt></td></tr><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>6</tt></td><td><tt>6</tt></td></tr><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr></tbody></table></td></tr><tr><td><table cellpadding="4" border="1"><tbody><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr><tr><td><tt>7</tt></td><td><tt>7</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr><tr><td><tt>7</tt></td><td><tt>7</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr></tbody></table></td><td><table cellpadding="4" border="1"><tbody><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr><tr><td><tt>.</tt></td><td><tt>8</tt></td><td><tt>8</tt></td><td><tt>.</tt></td></tr><tr><td><tt>.</tt></td><td><tt>8</tt></td><td><tt>8</tt></td><td><tt>.</tt></td></tr></tbody></table></td><td><table cellpadding="4" border="1"><tbody><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>.</tt></td></tr><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>9</tt></td><td><tt>9</tt></td></tr><tr><td><tt>.</tt></td><td><tt>.</tt></td><td><tt>9</tt></td><td><tt>9</tt></td></tr></tbody></table></td></tr></tbody></table>

When Boudreaux brings a window to the foreground, all of its squares come to the top, overlapping any squares it shares with other windows. For example, if window 1*and then* window 2 were brought to the foreground, the resulting representation would be:

<table width="80%"><tbody><tr><td><table cellpadding="4" border="1"><tbody><tr><td><tt>1</tt></td><td><tt>2</tt></td><td><tt>2</tt></td><td><tt>?</tt></td></tr><tr><td><tt>1</tt></td><td><tt>2</tt></td><td><tt>2</tt></td><td><tt>?</tt></td></tr><tr><td><tt>?</tt></td><td><tt>?</tt></td><td><tt>?</tt></td><td><tt>?</tt></td></tr><tr><td><tt>?</tt></td><td><tt>?</tt></td><td><tt>?</tt></td><td><tt>?</tt></td></tr></tbody></table></td><td>If window <tt>4</tt> were then brought to the foreground:</td><td><table cellpadding="4" border="1"><tbody><tr><td><tt>1</tt></td><td><tt>2</tt></td><td><tt>2</tt></td><td><tt>?</tt></td></tr><tr><td><tt>4</tt></td><td><tt>4</tt></td><td><tt>2</tt></td><td><tt>?</tt></td></tr><tr><td><tt>4</tt></td><td><tt>4</tt></td><td><tt>?</tt></td><td><tt>?</tt></td></tr><tr><td><tt>?</tt></td><td><tt>?</tt></td><td><tt>?</tt></td><td><tt>?</tt></td></tr></tbody></table></td></tr></tbody></table>

. . . and so on . . .  
Unfortunately, Boudreaux's computer is very unreliable and crashes often. He could easily tell if a crash occurred by looking at the windows and seeing a graphical representation that should not occur if windows were being brought to the foreground correctly. And this is where you come in . . .

## Input

Input to this problem will consist of a (non-empty) series of up to 100 data sets. Each data set will be formatted according to the following description, and there will be no blank lines separating data sets.  
  
A single data set has 3 components:  

1.  Start line - A single line:  
    START  
      
    
2.  Screen Shot - Four lines that represent the current graphical representation of the windows on Boudreaux's screen. Each position in this 4 x 4 matrix will represent the current piece of window showing in each square. To make input easier, the list of numbers on each line will be delimited by a single space.  
    
3.  End line - A single line:  
    END  
    

  
After the last data set, there will be a single line:  
ENDOFINPUT  
  
Note that each piece of visible window will appear only in screen areas where the window could appear when brought to the front. For instance, a 1 can only appear in the top left quadrant.

## Output

Input to this problem will consist of a (non-empty) series of up to 100 data sets. Each data set will be formatted according to the following description, and there will be no blank lines separating data sets.  
  
A single data set has 3 components:  

1.  Start line - A single line:  
    START  
      
    
2.  Screen Shot - Four lines that represent the current graphical representation of the windows on Boudreaux's screen. Each position in this 4 x 4 matrix will represent the current piece of window showing in each square. To make input easier, the list of numbers on each line will be delimited by a single space.  
    
3.  End line - A single line:  
    END  
    

  
After the last data set, there will be a single line:  
ENDOFINPUT  
  
Note that each piece of visible window will appear only in screen areas where the window could appear when brought to the front. For instance, a 1 can only appear in the top left quadrant.

## Sample Input

```
START
1 2 3 3
4 5 6 6
7 8 9 9
7 8 9 9
END
START
1 1 3 3
4 1 3 3
7 7 9 9
7 7 9 9
END
ENDOFINPUT


```

## Sample Output

```
THESE WINDOWS ARE CLEAN
THESE WINDOWS ARE BROKEN


```

## Source

[South Central USA 2003](http://poj.org/searchproblem?field=source&key=South+Central+USA+2003)
