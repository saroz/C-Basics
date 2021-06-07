---
title: Sum using Recursion
permalink: /sum-using-recursion/
layout: default
---

## Write a Program to do sum of natural numbers using recursion.

``` c
// Program
#include <stdio.h>

// declare function
int sum(int n);

void main()
{
    // define var
    int num, result;

    // ask user to enter numbers
    printf("Enter a positive number: ");
    scanf("%d", &num);

    // do math
    result = sum(num);

    // print output
    printf("The sum is: %d", result);
}

int sum(int n) {
    if( n != 0 ) {
        return n + sum(n-1); //recursive function
    } else {
        return n;
    }
}
```

### Output: <br/> 
Enter a positive number: 5 <br/>
The sum is: 15 <br/>
5 is an odd number. <br/>