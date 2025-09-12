#include <iostream>

using namespace std;

int main()
{   int u;
    cout << "username:";
    cin>>u;
    cout<<u+10;
    cout<<u;
    return 0;
}

output:
username:123
133123
Process returned 0 (0x0)   execution time : 24.789 s
Press any key to continue.


#include <iostream>

using namespace std;

int main()
{   int money;
    cout << "How much money do you have in your pocket:";
    cin>>money;
    cout<<"After 5 years you got:"<<money*10000;
    return 0;
}

output:

How much money do you have in your pocket:500
After 5 years you got:5000000
Process returned 0 (0x0)   execution time : 2.924 s
Press any key to continue.  


#include <iostream>

using namespace std;

int main()
{
    int a=5;
    int b;
    b = ++a;
    cout<<a;
    cout<<b;
    a=5;
    b= a++;
    cout<<a;
    cout<<b;
    b= --a;
    cout<<a;
    cout<<b;
    b=a--;
    cout<<a;
    cout<<b;
    return 0;
}

output;
66655545
Process returned 0 (0x0)   execution time : 0.015 s
Press any key to continue.
