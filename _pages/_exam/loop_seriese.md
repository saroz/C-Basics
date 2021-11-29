// Online C compiler to run C program online
#include <stdio.h>

int main() {
    int i;
    for (i = 4; i<=40; i+=4)
    {
         printf("%d\t",i);
    }
    
    printf("\n");
    int j=2;
    while (j<=20)
    {
          printf("%d\t",j);
          j+=2; // i=i+2;
    }

    printf("\n");

    int k=1;
    do
    {
        printf("%d\t",k);
        k=k+2;
    }while(k<=20);
    
    return 0;
}