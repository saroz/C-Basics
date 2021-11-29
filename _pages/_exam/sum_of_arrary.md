#include <stdio.h>
// ask 2 arrary and sum and make third arrary
int main() {
int i, one[5], two[5], three[5];
printf("Enter the 5 number for first arrary: ");

    for (i=0; i<5; i++) {
        scanf("%d", &one[i]);
    }

    printf("Enter the 5 number for second arrary: ");
    for (i=0; i<5; i++) {
        scanf("%d", &two[i]);
    }


    for (i=0; i<5; i++) {
        three[i] = one[i] + two[i];
        printf("%d index = %d\n ", i, three[i]);
    }


    return 0;

}
