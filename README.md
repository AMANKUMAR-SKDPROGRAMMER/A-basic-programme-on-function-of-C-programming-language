# A basic programme on function of C programming language
 A basic programme in Function of C programming language {with argument and with return value}
#include<stdio.h>
int sum(int a, int b);

int main()
{
    int a,b,c;
    a = 9;
    b = 87;

    c = sum(a,b);

    printf("The sum is %d\n",c);

    return 0;

}
int sum(int a, int b)
{
    return a+b;
    
}