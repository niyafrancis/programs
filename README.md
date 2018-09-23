# programs
#include<stdio.h>
int main()
{
  int a,b,c;
  scanf("%d%d%d",&a,&b,&c);
  if( (a==b | a==c) )
    printf("0");
  else if( b==c)
    printf("0");
  else
    printf("1");
return 0;
}

  
