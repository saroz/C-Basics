// Online C compiler to run C program online
#include <stdio.h>

int main() {
int num1, num2, num3;
printf("Please enter three number :");
scanf("%d %d %d", &num1, &num2, &num3);

    if (num1 > num2 && num1 > num3) {
        printf("First number %d is largest number", &num1);
    }
    else if (num2 > num1 && num2 > num3) {
        printf("Second number %d is largest number", num2);
    } else {
        printf("Third number (%d) is largest number", num3);
    }



    return 0;

}
