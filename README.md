#include<stdio.h>
#include<string.h>
int main()//to copy a string(or) duplication.

{
    char str1[10]="vijey";
    char str2[10];
    strcpy(str2, str1);
    printf("%s",str2);
    return 0;
    
}
