// Online C compiler to run C program online
#include <stdio.h>

int main() {
int a, b, c, avg, prod, sum;
printf("Plese enter first number: ");
scanf("%d", &a);
printf("Plese enter second number: ");
scanf("%d", &b);
printf("Plese enter third number: ");
scanf("%d", &c);

    sum = a + b + c;
    avg = sum/3;
    prod = a * b * c;

    printf("Sum of %d %d and %d is %d\n", a,b,c, sum);
    printf("Avg of %d %d and %d is %d\n", a,b,c, avg);
    printf("Product of %d %d and %d is %d\n", a,b,c, prod);

    return 0;

}
