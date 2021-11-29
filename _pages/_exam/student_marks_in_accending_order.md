#include <stdio.h>
// ask for 10 student marks an arrange in accending order
int main() {
int marks[10], i, j, temp;
printf("Enter marks of 10 student: ");
for(i=0; i<10; i++) {
scanf("%d", &marks[i]);
}

    for(i=0; i<10; i++) {
        for(j=i+1; j<10; j++) {
            if(marks[j] < marks[i]) {
                temp = marks[i];
                marks[i] = marks[j];
                marks[j] = temp;
            }
        }
    }

    printf("Pringing makrs of student in accending order: ");
    for(i=0; i<10; i++) {
        printf("%d is %d\n", i, marks[i]);
    }

    return 0;

}
