# CHECKING-FOR-VOTE-ELIGIBILITY
#include <iostream>

using namespace std;
#include<string.h>
int main()
{
    int age;
    char s[25];
    cout<<"CITIZEN OF WHICH COUNTRY (enter the country name in upper case) \n";
    cin>>s;
    cout<<"ENTER THE AGE OF THE CANDIDATE \n";
    cin>>age;
    if(strcmp(s,"INDIAN")==0 && age>=18)
       cout<<"Eligible for voting";
    else
      cout<<"Not Eligible for voting";
    
    return 0;
}
