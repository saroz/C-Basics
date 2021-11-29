#include <stdio.h>
// struct Write a program to store student name and roll in accending order

struct student {
char name[20];
int roll;
};

int main() {
struct student s[5], temp;
int i, j, count = 4;

    for(i=0; i<count; i++) {
        printf("Enter name and roll of Student:\n");
        scanf("%s %d", s[i].name, &s[i].roll);
    }
    for(i=0; i< count-1; i++) {
        for(j=i+1; j<count; j++) {
            if(s[i].roll > s[j].roll) {
                temp = s[i];
                s[i] = s[j];
                s[j] = temp;
            }
        }
    }

    printf("\n\nPrinting name of students... \n");
    for(i=0; i<count; i++) {
        printf("\n%d. ", i+1);
        printf("\n\tRoll number of studen is %d and\n", s[i].roll);
        printf("\tName of student is %s: ", s[i].name);

        printf("\n");
    }

    return 0;

}
