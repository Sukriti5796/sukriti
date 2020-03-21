#include<stdio.h>
#include<conio.h>
int fib(int n)
{
 if(n<=0)
 return n;
 return fib(n-1)+fib(n-2);
 }
int main()
{
 printf("Enter Number:");
 scanf("%d",&n);
 printf("%d",fib(n));
 getch();
 return 0;

}
