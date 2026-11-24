### swapping of two number using without temp variable

\# include<stdio.h>

int main()

{

int a,b;

printf("enter number for a and b:/n");

scanf("%d %d",\&a,\&b);

printf("/n before swapping:a=%d,b=%d/n",a,b);

a=a+b;

b=a-b;

a=a-b;

printf("/n after swapping:a=%d,b=%d/n",a,b);

return 0;

}



