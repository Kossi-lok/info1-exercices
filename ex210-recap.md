# Récap simple

## Q1
Quel est l'affichage de `res1` ?
`rest1 = 3`
## Q2
Quel est l'affichage de la boucle `for` ?
`0 7 14 21 28`
## Q3
Quel est l'affichage de `res2` ?
`7`
## Q4
Quel est l'utilité du `printf`de `res2` ?
`Elle permet d'éviter de faire une condition if() et d'afficher la valeur absolue`


```c
#include <stdio.h>

int main()
{
    int val1 = 10;
    int val2 = 7;
    
    int res1 = val1 % val2;
    printf("Res1 : %d\n", res1);
    
    printf("\nBoucle\n");
    for(int i=0; i<30; i++){
        if( i%7 == 0 )
            printf("%d\n",i);
    }
    
    printf("\nRes2 : %d\n", val2 > 0 ? val2 : -val2);

    return 0;
}
```

# Solutions
