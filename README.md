#include<stdio.h>
#include<conio.h>
void main()
{
int i,j,a[5][3];
clrscr();
  printf("enter the elements of a:");
  for(i=0;i<5;i++)
  {
  for(j=0;j<3;j++)
  {
  scanf("%d",&a[i][j]);
  }
  }
  for(i=0;i<3;i++)
  {
     printf("\tcols%d",i);
  }
     printf("\n");
     for(i=0;i<5;i++)
     {
       printf("\nrows%d",i);
         for(j=0;j<3;j++)
         {
         printf("%8d",a[i][j]);
         }
         }
      getch();
      }
     
