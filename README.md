# pattern1 using c
\\to print this pattern
0
1 2
3 4 5
6 7 8 9

\\code
#include<stdio.h>
#include<conio.h>
void main()
{
int i,j,num = 0;
for(i=1;i<5;i++)
{
for(j=1;j<=i;j++)
{printf("%d ",num);
num++;}
printf("\n");
}
getch();
}

