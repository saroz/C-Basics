// Online C compiler to run C program online
#include <stdio.h>

int main() {
char type;
int vowel;

    printf("Pleae a character to check vowel or not: ");
    scanf("%c", &type);

    vowel = type == 'a' || type == 'e' || type == 'i' || type == 'o' || type == 'u' || type == 'A' || type == 'E' || type == 'I' || type == 'O' || type == 'U';


    if(vowel) {
        printf("Character %c is vowel.", type);
    } else {
        printf("Character %c is not vowel.", type);
    }



    return 0;

}
