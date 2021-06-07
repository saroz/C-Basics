---
title: Large Number Among Three
permalink: /large-number-among-three/
layout: default
---

## Write a Program to find large number among three numbers.

``` c
// Program
#include <stdio.h>
void main()
{
    // define var
    int num1, num2, num3;

    // ask user to enter numbers
    printf("Enter a first number: ");
    scanf("%d", &num1);

    printf("Enter a second number: ");
    scanf("%d", &num2);

    printf("Enter a third number: ");
    scanf("%d", &num3);

    // print output
    if( num1 > num2 && num1 > num3 ) {
        printf("%d is the largest number.", num1);
    } else if( num2 > num1 && num2 > num3 ) {
        printf("\n%d is an odd number.", num2);
    } else {
        printf("\n%d is an odd number.", num3);
    }
}
```
### Output: <br/>
Enter a first number: 5 <br/>
Enter a second number: 9 <br/>
Enter a third number: 2 <br/>
9 is an odd number.