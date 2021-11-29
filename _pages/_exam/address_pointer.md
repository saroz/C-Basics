// Online C compiler to run C program online
#include <stdio.h>

int swap(int a, int b);

int main() {
int a;
float b;
double c;
char d;

    int *ptr_a = &a;
    float *ptr_b = &b;
    double *ptr_c = &c;
    char *ptr_d = &d;

    printf("address of int %u\n", &a);
    printf("address of float %u\n", &b);
    printf("address of double %u\n", &c);
    printf("address of char %u\n", &d);

    printf("\n");

    printf("address of int %u\n", ptr_a);
    printf("address of float %u\n", ptr_b);
    printf("address of double %u\n", ptr_c);
    printf("address of char %u\n", ptr_d);


    return 0;

}
