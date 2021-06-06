---
title: Size of Operators
permalink: /size-of-operators/
layout: default
---

## Write a Program to find size operator.

``` c
// Program
#include <stdio.h>
void main()
{
    // define var
    int int_size;
    float float_size;
    double double_size;
    char char_size;

    // print output
    printf("The size of int: %lu bytes\n", sizeof(int_size));
    printf("The size of float: %lu bytes\n", sizeof(float_size));
    printf("The size of double: %lu bytes\n", sizeof(double_size));
    printf("The size of char: %lu bytes\n", sizeof(char_size));
}
```

### Output: <br/> 
The size of int: 4 bytes <br/>
The size of float: 4 bytes <br/>
The size of double: 8 bytes <br/>
The size of char: 1 bytes <br/>