---
title: Add Two Float Numbers Custom
permalink: /add-two-flot-numbers-custom/
layout: default
---

## Write a Program to add two float numbers which restrict only have 3 value after decimal.

``` c
// Program

#include <stdio.h>
void main()
{
    // define var
    int a, b, sum;

    // ask user to enter value of a
    printf("Enter the value of a and b: ");
    scanf("%f %f", &a, &b);

    // do sum math
    sum = a + b;

    // print output
    printf("The sum of float numbers is: %0.3f", sum);
}

```

### Output: <br/> 
Enter the value of a and b: 3 <br/>
4 <br/>
The sum of float numbers is: 7.000
