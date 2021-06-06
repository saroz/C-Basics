---
title: Swap Numbers
permalink: /swap-numbers/
layout: default
---

## Write a Program to swap numbers.

``` c
// Program
#include <stdio.h>
void main()
{
    // define var
    int num1, num2, temp;

    // ask user to enter numbers
    printf("Enter a first number: ");
    scanf("%d", &num1);

    printf("Enter a second number: ");
    scanf("%d", &num2);

    temp = num1;
    num1 = num2;
    num2 = temp;

    // print output
    printf("After swapping, first number is: %d\n", num1);
    printf("After swapping, second number is: %d", num2);
}
```

### Output: <br/> 
Enter a first number: 100 <br/>
Enter a second number: 120 <br/>
After swapping, first number is: 120<br/>
After swapping, second number is: 100