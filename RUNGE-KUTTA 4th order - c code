#include<stdio.h>
#include <math.h>
#include<conio.h>
//dy/dx = y - x#define F(x,y)  (y)-(x)
void main()
{
  double y0,x0,y1,n,h,f,f1,k1,k2;
  int j;
  clrscr();
  printf("\nEnter the value of x0: ");
  scanf("%lf",&x0);
  printf("\nEnter the value of y0: ");
  scanf("%lf",&y0);
  printf("\nEnter the value of h: ");
  scanf("%lf",&h);
  printf("\nEnter the value of last point: ");
  scanf("%lf",&n);
  for(; x0<n; x0=x0+h)
  {
    f=F(x0,y0);
    k1 = h * f;
    f1 = F(x0+h,y0+k1);
    k2 = h * f1;
    y1 = y0 + ( k1 + k2)/2;
    printf("\n\n  k1 = %.4lf ",k1);
    printf("\n\n  k2 = %.4lf ",k2);
    printf("\n\n  y(%.4lf) = %.3lf ",x0+h,y1);
    y0=y1;
  }
getch();
}
