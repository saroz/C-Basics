---
title: Triangle is equilateral, isosceles or scalene
permalink: /triangle-equilateral-isosceles-scalene/
layout: default
---

## Check whether the triangle is equilateral, isosceles or scalene

``` c
// Program
// Online C compiler to run C program online
#include <stdio.h>
int main() {


    // define var
    int one, two, three;

    // ask for iput
    printf("Enter values:");
    scanf("%d%d%d", &one, &two, &three);
   
    // print output
    if(one == two && two == three)
        printf("Triangle is equilateral\n");
    else if(one == two || two == three || three == one)
        printf("Triangle is isosceles\n");
    else
        printf("Triangle is scalene\n");
    return 0;
}
```

### Output: <br/> 
Enter values:2 <br/>
2 <br/>
2 <br/>
Triangle is equilateral <br/>

