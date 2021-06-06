---
title: Add Two Float Numbers
permalink: /add-two-float-numbers/
layout: default
---

## Write a Program to add two flot numbers.

``` c
// Program

#include <stdio.h>
void main()
{
    // define var
    int a, b, sum;

    // ask user to enter value of a
    printf("Enter the value of a and b: ");
    scanf("%lf %lf", &a, &b);

    // do sum math
    sum = a + b;

    // print output
    printf("The sum of float numbers is: %lf", sum);
}

```

### Output: <br/> 
Enter the value of a and b: 3 <br/>
8 <br/>
The sum of float numbers is: 11.000000
