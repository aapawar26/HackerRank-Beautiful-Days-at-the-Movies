#include<bits/stdc++.h>
using namespace std;

int reverse(int number)
{
    int x = 0;
    int num = number;
    while(num)
    {
    x = x * 10;
    x = x +(num%10);
    num = num/10;
    }

    return x;
}

bool beautifulDay(int num, int div)
{
    int a = reverse(num);
    if((num - a)%div == 0)
    {
        return true;
    }
    return false;
}

int main()
{
    int d1,d2,div;
    cin>>d1>>d2>>div;
    int count = 0;

    for(int i=d1;i<=d2;i++)
    {
        if(beautifulDay(i,div))
            count++;
    }

    cout<<count<<endl;
    return 0;
}
