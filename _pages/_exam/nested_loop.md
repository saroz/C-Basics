// Online C compiler to run C program online
#include <stdio.h>

int main() {
    int i, j;
    for (i = 1; i<=5; i++)
    {
        for(j=1; j<=5; j++) {
            printf("%d\t",i*j);   
        }
        printf("\n");
    }
    
    printf("\n\n");

    
    int a = 1, c = 1;
    while (a<=5) {
        int b = 1;
        while(b<=5) {
            printf("%d\t", c);
            c++;
            b++;
        }
        a++;
        printf("\n");
    }
    
    printf("\n\n");
    
    int x = 1, y = 1;
    do {
        int z = 1;
        do {
            printf("%d\t", y);
            y++;
            z++;
        } while(z<=5);
        x++;
        printf("\n");
    } while(x<=5);
    
    // int j=2;
    // while (j<=20)
    // {
    //       printf("%d\t",j);
    //       j+=2; // i=i+2;
    // }

    // printf("\n");

    // int k=1;
    // do
    // {
    //     printf("%d\t",k);
    //     k=k+2;
    // }while(k<=20);
    
    return 0;
}