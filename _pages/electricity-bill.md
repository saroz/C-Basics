---
title: Electricity Bill
permalink: /electricity-bill/
layout: default
---

## Write a program in C to calculate and print the Electricity bill of a given customer. The customer id., name and unit consumed by the user should be taken from the keyboard and display the total amount to pay to the customer. The charges are as follow:


| Unit | Charge/unit|
|-|-|
| upto 199 | 1.20 |
| 200 and above but less than 400 | 1.50 |
| 400 and above but less than 600 | 1.80 |
| 600 and above | 2.00 |


``` c
// Program
#include <stdio.h>

int payable_amount(int unit, float rate) {
    int total_amount;
    total_amount = (unit * rate);

    if ( total_amount <= 100 ) {
        total_amount = 100;
    }

    if ( total_amount > 400 ) {
        total_amount = total_amount + (total_amount * 0.15);
    }
    
    return total_amount;
}

int main()
{
    char name;
    int id, total_unit,
        min_unit = 199,
        avg_unit = 400,
        max_unit = 600;
    float total_amount = 100,
        min_rate = 1.20,
        avg_rate = 1.50,
        max_rate = 1.80,
        buss_rate = 2.00;

    printf("Please enter your id, name & counsmed unit: ");
    scanf("%d %s %d", &id, &name, &total_unit);

    if (total_unit <= min_unit)
    {
        total_amount = payable_amount(total_unit, min_rate);
    }
    else if (total_unit > min_unit && total_unit < avg_unit)
    {
        total_amount = payable_amount(total_unit, avg_rate);
    }
    else if (total_unit >= 400 && total_unit < max_unit)
    {
        total_amount = payable_amount(total_unit, max_rate);
    }
    else {
        total_amount = payable_amount(total_unit, buss_rate);
    }

    printf("Total amount to be pay: %0.2f", total_amount);
}
```

### Output: <br/> 
Please enter your id, name & counsmed unit: 3 <br/>
Saroz <br/>
500 <br/>
Total amount to be pay: 1035.00 <br/>
