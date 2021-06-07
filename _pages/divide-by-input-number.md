---
title: Divide by User Input Number
permalink: /divide-by-input-number/
layout: default
---

## Program to divide by user input number.

``` c
// Program
#include <stdio.h>
void main()
{
    // define var
    int a, b;

    // ask user to enter numbers
    printf("Enter the value a: ");
    scanf("%d", &a);

    printf("Enter the value b: ");
    scanf("%d", &b);

    // print output
    if( a % b == 0 ) {
        printf("%d is divisible by %d.", a, b);
    } else {
        printf("The number %d is not divisible by %d.", a, b);
    }
}
```

### Output: <br/> 
Enter the value a: 4 <br/>
Enter the value b: 2 <br/>
4 is divisible by 2. <br/>