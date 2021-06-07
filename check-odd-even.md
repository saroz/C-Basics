---
title: Odd or Even Number
permalink: /check-odd-even/
layout: default
---

## Program to check odd or even.

``` c
// Program
#include <stdio.h>
void main()
{
    // define var
    int num;

    // ask user to enter numbers
    printf("Enter the number to check odd or even: ");
    scanf("%d", &num);

    // print output
    if( num % 2 == 0 ) {
        printf("\n%d is an even number.", num);
    } else {
        printf("\n%d is an odd number.", num);
    }
}
```

### Output: <br/> 
Enter the number to check odd or even: 5 <br/>
5 is an odd number.

***or***

Enter the number to check odd or even: 8 <br/>
8 is an even number.
