# copying-of-string-making-own-mystrcpy-function.c
//C program of copying of string making own mystrcpy function.output=

enter=akasd
akasd

#include <stdio.h>

char mystrcpy(char[],char[]);
char main() {
    int n;
    char a[20],b[20];
    printf("enter=");
    scanf("%s",a);
    mystrcpy(a,b);
     printf("%s",b);
    return 0;
}
char mystrcpy(char a[],char b[])
{
    int i;
    for(i=0;a[i];i++)
    b[i]=a[i];
    b[i]=a[i];
    return b[i];
}
