#include <stdio.h>

int main() 
{
  double x,i,f=1,j,a=0,n;
  printf("enter x and n \n");
  scanf("%lf %lf",&x,&n);
  for(i=1;i<=n;i++)
  {
    for(j=1;j<=i;j++)
    {
      f=f*i;
    }
    a=a+((i*x)/f);
  }
  printf("%lf",a);
}
