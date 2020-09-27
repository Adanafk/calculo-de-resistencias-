# calculo-de-resistencias-
//Adan Leal Gomez 
#include <stdio.h>
int  main ()
{
    float r1,r2,r3,v,I1,I2,I3,v1,v2,v3;

    printf("escrive el valor de cada resistencia \nresistencia 1\nresistencia 2\n resistencia 3\n");
    scanf("%f",& r1);
    scanf("%f",& r2);
    scanf("%f",& r3);
     printf("escrive el voltaje de la funte \n");
    scanf("%f",& v);

    I1 = v/r1;
    I2 = v/r2;
    I3 = v/r3;

printf("intencidad de la resistencia 1 en Amperes= %f\n",I1 );
printf("intencidad de la resistencia 2 en Amperes= %f\n",I2 );
printf("intencidad de la resistencia 2 en Amperes= %f\n",I3 );

v1= I1*r1;
v2= I2*r2;
v3= I3*I3;
printf("voltaje en la resistencia 1=  %f\n",v1 );
printf("voltaje en  la resistencia 2= %f\n",v2 );
printf("voltaje en la resistencia 3= %f\n",v3 );

}

