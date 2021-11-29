#include <stdio.h>

int main()
{
int a[10];
int i, odd = 0, even = 0;
printf("Please enter 10 numbers: ");
for(i=0; i<10; i++) {
scanf("%d", &a[i]);
if(a[i]%2 == 0) {
even++;
} else {
odd++;
}
}

    printf("%d is even number \n", even);
    printf("%d is odd number", odd);

    return 0;


    return 0;

}
