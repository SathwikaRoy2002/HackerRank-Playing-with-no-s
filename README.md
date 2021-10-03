#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() 
{
 char ch;
 char s[25], sen [150];
 scanf("%c",&ch);
 scanf("%s",s);
 scanf("\n");
 scanf("%[^\n]%*c",sen);
 printf("%c\n",ch);
 printf("%s\n",s);
 printf("%s\n",sen);
    return 0;
}
