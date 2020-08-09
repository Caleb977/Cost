#include<stdio.h>
int main(){
    double a;
    double b;
    double c;
    int d;
    
    puts("Kindly enter the total amount of money you have:");
    scanf("%lf",&a);
    
    puts("Kindly enter the cost of book:");
    scanf("%lf",&b);
    
    c = (a/b);
    d = (int) c;
    
    printf("You can buy %d books",d);
   
    
    return 0;
}
