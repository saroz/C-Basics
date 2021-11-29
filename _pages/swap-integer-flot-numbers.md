---
title: Swap Integer & Flot Numbers
permalink: /swap-integer-flot-numbers/
layout: default
---

## Write a Program to print integer.

``` c
// Program
#include <stdio.h>
int swapNum(int *, int *, float *, float *);
int main()
{
    // define 
    int a = 30, b = 50;
    float x = 12.00, y = 40.00;
    
    //    
    printf("a before swap : %d \n", a);
    printf("a before swap : %d \n", b);
    printf("a before swap : %f \n", x);
    printf("a before swap : %f \n", y);
    
    swapNum(&a, &b, &x, &y);
    
    printf("a after swap : %d \n", a);
    printf("a after swap : %d \n", b);
    printf("a after swap : %f \n", x);
    printf("a after swap : %f \n", y);
}


int swapNum(int *a, int *b, float *x, float *y) {
    int temp1; float temp2;
    
    temp1 = *a;
    *a = *b;
    *b = temp1;

    temp2 = *x;
    *x = *y;
    *y = temp2;

}

```

### Output: <br/> 
Enter the value of a: 5 <br/>
You entered the number 5.