#include<iostream>
using namespace std;

int main()
{
    int n;
    cin>>n;

    int  i=2;
    while(i<n){
        if(n%i!=0){
            cout<<"The number is Prime for "<<i<<endl;
        }
        else{
            cout<<"THe number is Prime for "<<i<<endl;
        }
        i++;
    }

    return 0;
}
