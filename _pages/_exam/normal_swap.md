// Online C compiler to run C program online
#include <stdio.h>

int main() {
    int num1, num2, temp;
    printf("Please enter first number: ");
    scanf("%d", &num1);
    printf("Please enter second number: ");
    scanf("%d", &num2);
    
    printf("Before: %d and %d\n", num1, num2);
    
    temp = num1;
    num1 = num2;
    num2 = temp;
    
    
    printf("after: %d and %d", num1, num2);
    
    return 0;
}