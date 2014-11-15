string_bufferoverflow
=====================


#include <iostream>
#include <iomanip>    //for setw


using namespace std;

int main()
{
    const int MAX =7;
    char str[MAX];
    cout<<"Enter a string:";
    cin>>str;
    
    cout<<setw(MAX)<<"You entered: "<<str<<endl;
    return 0;
}
