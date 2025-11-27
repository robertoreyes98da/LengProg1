# LengProg1
#include <stdio.h>

int main()
{
    int num;
    printf("Escribe tu edad:\n ");
    scanf("%d", &num);
    
    if (num >=18)
    printf ("Eres mayor de edad");
    
    if (num <18)
    printf ("Aun eres menor de edad");
}
