#### Write a Program to add two user input numbers:

``` c
// Program

#include <stdio.h>
void main()
{
    // define var type intiger
    int a, b;

    // ask user to enter first number - a
    printf("Enter the value of a: ");
    scanf("%d", &a);

    // ask user to enter second number - b
    printf("Enter the value of b: ");
    scanf("%d",&b);

    // print output
    printf("The sum of a and b is: %d", a+b);
}
```
Output: <br/>
```Enter the value of a: 4``` <br/>
```Enter the value of b: 6``` <br/>
```The sum of a and b is: 10``` 