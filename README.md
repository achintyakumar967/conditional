# conditional
#include <stdio.h>

int main() {
  int a;
  printf("enter your number :");
  scanf("%d",&a);
 if(a>60 && a<100){
     printf("and operator\n");
 }
 if(a>40 || a<35){
     printf("or operator");
 }
 if(a!=a){
     printf("or operators");
 }
    return 0;
}
