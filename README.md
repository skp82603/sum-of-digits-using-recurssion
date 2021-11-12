#include<stdio.h>

int foo(int n);

int main()

{

  int n;

  printf("inter a number:");

  scanf("%d",&n);

  foo(n);

  printf("the sum is:%d",foo(n));

  return 0;

   

}



int foo(int n)

{

  if(n==0)

  return n;

  else 

  return n%10+foo(n/10);

}
