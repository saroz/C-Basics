//read a marks of 5 student . calculate sum and avg using array;
#include <stdio.h>
int main()
{
int marks[5], sum = 0, i;
float avg;
printf("Please enter marks of 5 students: ");

    //
    for(i=0; i<5; i++) {
        scanf("%d", &marks[i]);
    }

    // adding marks of students
    for(i=0; i<5; i++) {
        sum += marks[i];
    }

    // calculating avg
    avg = sum/5;



    printf("Sum of students marks %d \n", sum);
    printf("Average marks of students %f", avg);

    return 0;

}
