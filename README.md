# Find-bs-gs-ta-hra
#include<studio.h>
int main()
{
   float gs,bs,ta,hrs;
   printf("Enter Basic Salary=\t");
   scanf("%f",&bs);

   ta=bs*(0.4);
   printf("Travelling allowance=%f \t",ta);

   hra=bs*(0.2);
   printf("\nHouse rent allowance= %f\t",hra);

   gs=bs+ta+hra;
   printf("\nGross salary=%f\t",gs);

   return 0;
}
   
   
