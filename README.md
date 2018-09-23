#include<stdio.h>
#include<conio.h>
float area(int b,int h)
{ 
  float area;
  area=(b*h)/2;
  return area;
}
void main
{ 
  int x,y;
  float z;
  printf("Enter the value of base and height of the traingle\n");
  scanf("%d%d",&x,&y);
  z=area(x,y);
  printf("The area of the triangle:%f",z);
  getch();
}
