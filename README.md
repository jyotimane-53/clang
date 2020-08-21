# clang
if name is equal to name write then print hello! else print no. 
#include<stdio.h>
#include<conio.h>
#include<string.h>
int main()
{
  int x; 
    char j[10]="good";
    char name[10];
    printf("enter name ");
    scanf("%s",name);
    x=strcmp(j,name);
    if(x==0)
      printf("hello!");
    else
      printf("no");
      return 0;
 }
