# Add-Two-Number-in-Function
#include <stdio.h>

int main() {
   int a,b,c;
   scanf("%d%d",&a,&b);
   c=sum(a,b);
   printf("%d",c);
   return 0;
}
int sum(int a,int b){
    int c=a+b;
    return c;
}
