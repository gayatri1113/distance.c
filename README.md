//# distance.c//
#include<stdio.h>
int main()
{
    float km,m,cm,ft,inch;
    printf("Enter the distance in kilometers");
    scanf("%f",&km);
    m=km*1000;
    cm=m*100;
    inch=cm/2.54;
    ft=inch/12;
    printf("distance in meters=%f\n",m);
    printf("distance in centmeters=%f\n",cm);
    printf("distance in inches=%f\n",inch);
    printf("distance in feets=%f\n",ft);
    return 0;
}
