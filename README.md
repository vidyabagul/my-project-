# my-project-program for fizzbuzz 
#include<stdio.h>
void main()
{
int i;
printf("enter first no\n");
for(i=1;i<=100;i++)
{
if(i%3==0)
printf("fizz\n");
if(i%5==0)
printf("buzz\n");
if(i%3==0&&i%5==0)
{
printf("fizzbuzz \n");
}printf("%d\n",i);
}
