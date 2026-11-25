### search for a keyword inside a given string

\#include<stdio.h>

\#include<string.h>

int main()

{

char str\[]="c programming is easy to learn";

char keyword\[50];

printf("string:%s\\n",str);

printf("enter keyword to search:");

scanf("%s",keyword);



if(strstr(str,keyword)!=NULL)

{

printf(YES,keyword is found.\\n");

}

else

{

printf(NO,keyword not found./n");

}

return 0;

}

