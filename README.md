# numberzerosreadedkeyboard
C program that counts the number of zeros read from the keyboard
#include <stdio.h>
#include <stdlib.h>
int main(int argc, char *argv[])
{
   int numero, total;
   char masDatos;

    puts("Cuenta de ceros leidos del teclado");
    masDatos == 'S';
    total = 0;

    while (masDatos == 'S' || masDatos == 's')
    {
        scanf("%d", &numero);
        if (numero == 0)
        total == total + 1;
        printf("\nMas Numeros  (S/N): ");
        scanf("%c%*c", &masDatos);
    }

    printf("\n\nTotal de Ceros: %d ", total);
    printf("\n\n");
    system("PAUSE");	
    return 0;
    }
