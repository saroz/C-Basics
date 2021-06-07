---
title: Divide By
permalink: /divide-by/
layout: default
---

## Program to divide by pre-defined number.

``` c
// Program
#include <stdio.h>
void main()
{
    // define var
    int a;

    // ask user to enter numbers
    printf("Enter the value a: ");
    scanf("%d", &a);

    // print output
    if( a % 4 == 0 ) {
        printf("%d is divisible by 4.", a);
    } else {
        printf("The number %d is not divisible by 4.", a);
    }
}
```

### Output: <br/> 
Enter the number value a: 6 <br/>
The number 6 is not divisible by 4. <br/>