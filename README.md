#include <stdio.h>
int main(){
  const int discount = 10;
  
  float price;
  float finalprice;
  
  scanf("%f", &price);
  
  finalprice = price - (discount * price) / 100;
  printf("Final price after discount is: %.2f", finalprice);
  return 0;
  
  
}
