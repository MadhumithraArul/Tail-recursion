Tail recursion:Logic before recursion
#printing n to 1 if n is odd or print n to 2 if n is even using recursion 
#include<stdio.h>

void printfor(int n)
{if(n<1)
return ;

printf("%d ",n);
printfor(n-2);
}
int main()
{int n;
scanf("%d",&n);
printfor(n);
}
