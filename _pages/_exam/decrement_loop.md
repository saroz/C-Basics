// Online C compiler to run C program online
#include <stdio.h>

int main() {
int i, j = 1, k = 1;

    printf("Increments.\n");
    // for loop
    for(i=1; i<=10; i++) {
        printf("%d\t", i);
    }

    //while loop
    printf("\n");
    while(j<=10) {
        printf("%d\t", j);
        j++;
    }

    // do while
    printf("\n");
    do {
        printf("%d\t", k);
        k++;
    } while(k<=10);


    printf("\nDecrements.\n");
    for(i=10; i>=1; i--) {
        printf("%d\t", i);
    }

    printf("\n");
    // while loop
    j = 10;
    while(j >= 1) {
        printf("%d\t", j);
        j--;
    }
    printf("\n");
    // while loop
    k = 10;
    do {
        printf("%d\t", k);
        k--;
    } while(1<=k);

    return 0;

}
