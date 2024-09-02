
#include <stdio.h>
int main()
{
    int distance;
    float fuel,consumption;

    printf("Enter the value of distance covered:");
   scanf("%d\n", &distance);
   printf("Enter the value of fuel:");
   scanf("%f\n",&fuel);
   consumption = (fuel / distance) * 100;
   printf("Consumption: %.2f\n", &consumption);
   
   return 0;

}
