# power-raised-2
#include<iostream>
using namespace std;
int power(int x)
{
    //base case
    if(x==1)
    return 2;
    //recursive call
    int recCall = power(x-1);
    //small calculation
    int smallCal = recCall*2;
    return smallCal;
}
int main()
{
    int n;
    cin>>n;
    cout<<power(n);
    return 0;
}
