---
title: Oldest Yongest Average Age
permalink: /oldest-yongest-average-age/
layout: default
---

## Write a Program to print integer.

``` c
// Program
#include <stdio.h>

int main(void) {
    int ages[15], age, oldest, yongest, sum_ages = 0, count = 15;
    float avg_age;

    printf("Please enter a age of %d persons.\n", count);
    for(int i = 0; i < count; i++) {
        printf("Age of person %d: ", i + 1);
        scanf("%d", &age);
        ages[i] = age;    
    }

    oldest = ages[0];
    yongest = ages[0];
    sum_ages = ages[0];

    for (int i = 1; i < count; ++i) {
        // oldest
        if(oldest < ages[i]) {
        oldest = ages[i];
        }

        // youngest
        if(yongest > ages[i]) {
        yongest = ages[i];
        }

        // average
        sum_ages += ages[i];
    }

    avg_age = sum_ages / count;
    printf("\nOldest: %d years\n", oldest);
    printf("Yongest: %d years &\n", yongest);
    printf("Average: %0.2f years", avg_age);
    return 0;
}

```

### Output: <br/> 
Please enter a age of 15 persons. <br/>
Age of person 1: 10 <br/>
Age of person 2: 5 <br/>
Age of person 3: 15 <br/>
Age of person 4: 40 <br/>
Age of person 5: 20 <br/>
Age of person 6: 25 <br/>
Age of person 7: 27 <br/>
Age of person 8: 34 <br/>
Age of person 9: 32 <br/>
Age of person 10: 32 <br/>
Age of person 11: 22 <br/>
Age of person 12: 23 <br/>
Age of person 13: 32 <br/>
Age of person 14: 33 <br/>
Age of person 15: 29 <br/>

Oldest: 40 years <br/>
Yongest: 5 years & <br/>
Average: 25.00 years <br/> 