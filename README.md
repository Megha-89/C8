# C8
Mirror of right angle triangle 
#include<stdio.h>
int main()
{
 int i,n,j,k;
 printf("enter the row of matrix:");
 scanf("%d",&n);
 for(i=1;i<=n;i++){
 for(j=1;j<=n-i;j++){
 printf (" ");
 }
 for(k=1;k<=i;k++){
 printf ("*");
 }
 printf("\n");
 }
 return 0;
 }
