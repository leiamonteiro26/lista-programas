# lista-programas
#include <stdio.h>
#include <stdlib.h>
#include <locale.h>

Void verificar(int n);

int main() {
      setlocale(LC_ALL, Portuguese_Brazil”);

      int num;

      printf(“digite o número: “);
      scanf(“%d”, &num);
}

void verificar(int n) {
  
       if(n >= 0) {
             printf(“\nNÚMERO POSITIVO.);
       }else{
             printf(“\nNÚMERO NEGATIVO.”);
       }
}
