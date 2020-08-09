#include<stdio.h>
int main(){
    double a;
    double b;
    int A;
    int B;
    double c;
    int d;
    int e;
    
    puts("Kindly enter the total amount of money you have in €:");
    scanf("%lf",&a);
    
    puts("Kindly enter the cost of book in €:");
    scanf("%lf",&b);
    
    c = (a/b);
    d = (int) c;
    
    A = (int) a;
    B = (int) b;
    e = A%B;
    
    printf("You can buy %d books\n",d);
    
    printf("You will have %d€ left.",e);  
    
    return 0;
}
