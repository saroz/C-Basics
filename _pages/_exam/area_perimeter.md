// Online C compiler to run C program online
#include <stdio.h>

int main() {
int length, breadth, area, perimeter;

    printf("Please enter the length of rectangle: ");
    scanf("%d", &length);
    printf("Please enter the breadth of rectangle: ");
    scanf("%d", &breadth);

    area = length * breadth;
    perimeter = 2 * (length + breadth);

    printf("Area of rectangle is %d\n", area);
    printf("Perimeter of rectangle is %d\n", perimeter);



    return 0;

}
