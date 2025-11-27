# C2
// PROGRAM
#include<stdio.h>
int main(){
    int x=0;
    int*p=&x;
    printf("value of x:%d \n",x);
    printf("address of x %p \n",&x);
    printf("value of address p:%p \n",p);
    printf("value of p:%d \n",*p);
    *p=200;
    printf("new value of x:%d \n",x);
    return 0;
}
