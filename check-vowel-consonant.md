---
title: Vowel or Consonant
permalink: /check-vowel-consonant/
layout: default
---

## Write a Program to find size operator.

``` c
// Program
#include <stdio.h>
void main()
{
    // define var
    char alphabet;
    int l_case_vowel, u_case_vowel;

    // ask user to enter numbers
    printf("Enter a letter from english alphabet: ");
    scanf("%c", &alphabet);

    l_case_vowel = ( alphabet == 'a'|| alphabet == 'e' || alphabet == 'i' || alphabet == 'o' || alphabet == 'u' ); //reflect 1 if true

    u_case_vowel = ( alphabet == 'A'|| alphabet == 'E' || alphabet == 'I' || alphabet == 'O' || alphabet == 'U' ); //reflect 1 if true


    // print output
    if( l_case_vowel || u_case_vowel ) {
        printf("%c is a vowel.", alphabet);
    } else {
        printf("%c is consonant.", alphabet);
    }
}
```

### Output: <br/> 
Enter a letter from english alphabet: O <br/>
O is a vowel. <br/>
***or***

Enter a letter from english alphabet: b <br/>
b is consonant.