### **swapping of two numbers using temp variable**



\# include<stdio.h>

int main()

{

int a,b;

printf("enter number for a and b:/n");

scanf("%d %d",\&a,\&b);

printf("/n before swapping:a=%d,b=%d/n",a,b);

temp=a;

a=b;

b=temp;

printf("/n after swapping:a=%d,b=%d/n",a,b);

return 0;

}





