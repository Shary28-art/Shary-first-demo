
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


#include <stdio.h>
int main()
{
    int a;
    printf("Which subject you have passed in:");
    printf("Type 1 for passing maths and science,2 for maths, 3 for science");
    scanf("%d",&a);
    if (a==1){
      printf("Wow!You have won a prize of 45\n");
    }
    else if(a==2){
        printf("Wow! You have won a prize of 15\n");
    }
    else if(a==3){
        printf("Wow!You have won a prize of 15\n");
    }
    else{
        printf("Sorry!But you have not won anything");
    }
    return 0;
}
