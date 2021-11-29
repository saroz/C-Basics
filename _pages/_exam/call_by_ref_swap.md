// swap number using call by refrence

#include <stdio.h>
void swap(int *x, int *y);

int main() {
int a = 100; b = 200;
printf("Before swap a = %d and b = %d", a, b);
swap(&a, &b);
printf("After swap a = %d and b = %d", a, b);
return 0;
}

void swap(int *x, int *y) {
int temp;
temp = *x;
*x = *y;
*y = temp;
}
