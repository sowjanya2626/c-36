# c-36
Head recursion 
#include<stdio.h>
void head(int n){
    if(n==0)
        return;
    head(n-1);
    printf("%d",n);
    }
    int main(){
        head(10);
        return 0;
    }
