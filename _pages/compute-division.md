---
title: Compute Division
permalink: /compute-division/
layout: default
---

## Write a Program to compute division.

``` c
// Program

#include <stdio.h>
void main()
{
    // define var
    float dividend, divisor, quotient;

    // ask user to enter character
    printf("Enter a dividend number: ");
    scanf("%f", &dividend);

    printf("Enter a divisor number: ");
    scanf("%f", &divisor);

    // do math
    quotient = dividend / divisor;
 
    // print output
    printf("Quotient is: %f \n", quotient);
}

```

### Output: <br/> 
Enter a dividend number: 2.8 <br/>
Enter a divisor number: 1.2 <br/>
Quotient is: 2.333333