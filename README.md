# Fa-a-uma-fun-o-que-receba-10-valores-e-retorne-o-quadrado-da-soma-deles-
#include <stdio.h>
#include <math.h>

int main()
{
   //Faça uma função que receba 10 valores e retorne o quadrado da soma deles 
   
   int i;
   
   
   float v, total;
   
   for(i=0;i<=3;i++) {
   
   printf("\nDigite o valor:");
   scanf("%f", &v);
   total = total+v;
   
   }
   printf("\n Quadrado do soma = %f ",pow (total,2));
   
    return 0;
}

