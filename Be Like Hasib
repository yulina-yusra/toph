#include <stdio.h>
long long int count=0,l=1,m;
int main()
{
    long long int n,x,res;
    scanf("%lld %lld", &n,&x);
    res=binarySearch(n,x);
    printf("%lld", res);
}
int binarySearch(long long int n,long long int x)
{

    while(l<n)
    {

        m=(n+l)/2;
        count++;
        if(m<x)
        {
            l=m+1;
        }
        else
        {
            n=m;
        }
    }
    return count;
}
