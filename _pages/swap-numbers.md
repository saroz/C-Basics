---
title: 3D Array
permalink: /three-d-array/
layout: default
---

## Print 3D Array

``` c
// Program
// Online C compiler to run C program online
#include <stdio.h>
int main() {
    int x[2][3][2];
    for (int i = 0; i < 2; i++) {
        for (int j = 0; j < 3; j++) {
            for (int k = 0; k < 2; k++) {
                printf("Enter values x[%d][%d][%d]: ", i, j, k);
                scanf("%d", &x[i][j][k]);
            }
        }
    }
    printf("3D array: \n{\n");
    for (int i = 0; i < 2; i++) {
        printf("\t{");
        for (int j = 0; j < 3; j++) {
            if(j == 1 || j == 2 ) {
                printf(",");
            }

            for (int k = 0; k < 2; k++) {
                if(k == 0) {
                    printf("{");
                }
                if(k == 1) {
                    printf(",");
                }
                printf("%d", x[i][j][k] );
                if(k == 1) {
                    printf("}");
                }
            }
        }
        printf("}\n");
    }
    printf("\n}");
}
```

### Output: <br/> 
Enter values x[0][0][0]: 0 <br/>
Enter values x[0][0][1]: 1 <br/>
Enter values x[0][1][0]: 2 <br/>
Enter values x[0][1][1]: 3 <br/>
Enter values x[0][2][0]: 4 <br/>
Enter values x[0][2][1]: 5 <br/>
Enter values x[1][0][0]: 6 <br/>
Enter values x[1][0][1]: 7 <br/>
Enter values x[1][1][0]: 8 <br/>
Enter values x[1][1][1]: 9 <br/>
Enter values x[1][2][0]: 10 <br/>
Enter values x[1][2][1]: 11 <br/>
3D array: <br/>
{ <br/>
    &nbsp;&nbsp;&nbsp;{\{0,1},{2,3},{4,5}\}<br/>
	&nbsp;&nbsp;&nbsp;{\{6,7},{8,9},{10,11}\}<br/>
}