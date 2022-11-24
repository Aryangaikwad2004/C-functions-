# C++ functions-
//solving my first problem......



#include<iostream>
using namespace std;

int max (int a , int b, int c, int d){
    if(a>b && a>c &&a>d)
    cout<<"The no "<<a<<" is greatest no";

    if (b>a && b>c && b>d)
    cout<<"The no "<<b<<" is the greatest no";

    if(c>a && c>b && c>d)
    cout<<"The no"<<c<<" is greatest no ";

    if(d>a && d>b && d>c)
    cout<<"The  no "<<d<<" is greatest no ";

    return 0;

}
int main(){
    int a, b, c, d;
    cout<<"Enter the four nos: "<<endl;
    cin>>a>>b>>c>>d;

    max (a,b,c,d);

return 0;
}
