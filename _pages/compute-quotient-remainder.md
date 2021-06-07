---
title: Compute Quotient and remainder
permalink: /compute-quotient-remainder/
layout: default
---

## Write a Program to compute quotient and reminder.

``` c
// Program

#include <stdio.h>
void main()
{
    // define var
    int dividend, divisor, quotient, remainder;

    // ask user to enter character
    printf("Enter a dividend number: ");
    scanf("%d", &dividend);

    printf("Enter a divisor number: ");
    scanf("%d", &divisor);

    // do math
    quotient = dividend / divisor;
    remainder = dividend % divisor;
 
    // print output
    printf("Quotient is: %d \n", quotient);
    printf("Remainder is: %d", remainder);
}

```

### Output: <br/> 
Enter a dividend number: 15 <br/>
Enter a divisor number: 2 <br/>
Quotient is: 7 <br/>
Remainder is: 1
