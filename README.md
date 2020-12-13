# Program to add digits of a given number
#include<iostream>
using namespace std;
int main()
{
    int n,m,sum,rem;
    cout<<"Enter the number:";
    cin>>n;
    m=n;
    sum=0;
    while(n!=0)
    {
        rem=n%10;
        sum=sum+rem;
        n=n/10;
    }
    cout<<"Sum of digits in "<<m<<" is "<<sum<<endl;
    return 0;
}

