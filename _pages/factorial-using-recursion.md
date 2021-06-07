---
title: Number Factorial - Recursion
permalink: /factorial-using-recursion/
layout: default
---

## Write a Program to calculates the factorial of a given number using a recursive function.

``` c
// Program
#include <stdio.h>

// declare function
//unsigned long long int fact(unsigned int x)
int fact(int n) {
    if( n <= 0 ) {
        return 1;
    }
    return n * fact(n-1); //recursive function
}

void main()
{
    // define var
    int n, result;

    // ask user to enter numbers
    printf("Enter the value of n: ");
    scanf("%d", &n);

    // do math
    result = fact(n);

    // print output
    printf("Factorial of %d is %d", n, result);
}
```

### Output: <br/> 
Enter the value of n: 4 <br/>
Factorial of 4 is 24 <br/>