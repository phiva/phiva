phiva
=====
#include <stdio.h>
#include <math.h>

int main(){

  int x, S;
  
  printf("Enter a value of x : ");
  scanf("%d", &x);
  
  S = 5*pow(x, 4) + 3*pow(x, 3) - 2*pow(x, 2) + 4*x - 9;
  
  printf("S = %d\n\n", S);
  
  return 0;
  
  }
