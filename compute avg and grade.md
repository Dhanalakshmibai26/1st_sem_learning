### input marks of 3 subject, check pass/fail(>=40 in each), compute avg and grade

\# include<stdio.h>

int main()

{

int P,C,M;

float avg;

printf("enter marks for of physics:");

scanf("%d",\&P); 

printf("enter marks for of chemistry:");

scanf("%d",\&C);

printf("enter marks for of maths:");

scanf("%d",\&M);



if(P>=40)

{printf("physics:PASS\\n");}

else

{printf("physics:FAIL\\n");}



if(C>=40)

{printf("chemistry:PASS\\n");}

else

{printf("chemistry:FAIL\\n");}



if(M>=40)

{printf("maths:PASS\\n");}

else

{printf("maths:FAIL\\n");}



avg=(P+C+M)/3.0;

printf("average=%f\\n",avg);

if(avg>=75)

{printf("grade=A\\n");}

else if(avg>=60)

{printf(grade=B\\n");}

else if(avg>=50)

{printf("grade=C\\n");}

else

{printf("grade=D\\n");}

return 0;

}



### 

