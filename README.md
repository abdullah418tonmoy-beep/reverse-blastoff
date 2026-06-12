#include<stdio.h>

int main()
{
    int n;

    printf("Enter last num: ");
    scanf("%d",&n);
    while(n>=0)
    {
        if(n>=1) printf("%d\n",n);
        else { printf(" Blastoff!");}
        n--;
    }


    return 0;
}
