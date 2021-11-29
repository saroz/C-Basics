// Online C compiler to run C program online
#include <stdio.h>

int main() {

    int num1, num2, sum = 0, diff = 0, pro = 0, quo = 0, rem = 0;
    printf("Please enter first number: ");
    scanf("%d", &num1);
    printf("Please enter second numbere: ");
    scanf("%d", &num2);

    // sum
    sum = num1 + num2;
    printf("Sum is %d\n", sum);

    // diff
    diff = num1 - num2;
    printf("Diff is %d\n", diff);

    // pro
    pro = num1 * num2;
    printf("Pro is %d\n", pro);

    // quo
    quo = num1 / num2;
    printf("Quo is %d\n", quo);

    // rem
    rem = num1 % num2;
    printf("Rem is %d\n", rem);


    return 0;

}
