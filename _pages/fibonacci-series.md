---
title: Fibonacci Series
permalink: /fibonacci-series/
layout: default
---

## Write a Program to generates the Fibonacci series for a given number using a recursive function.

``` c
// Program
#include <stdio.h>

// declare function
int fibo(int i) {
    if( i == 0 ) {
        return 0;
    } else {
        return 1;
    }
    return fibo(i-1) + fibo(i-2); //recursive function
}

void main()
{
    // define var
    int i;

    // print output
    for(i = 0; i < 11; i++) {
        printf("%d\n",fibo(i));
    }
}
```

### Output: <br/> 
Enter the value of n: 4 <br/>
Factorial of 4 is 24 <br/>