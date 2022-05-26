#include <iostream>
using namespace std;

void function(int variable);

int main()
{
    int variable;
    cout << "Input variable value : \n";
    cin >> variable;
    cout << "Value of your variable before the process : " << variable << endl;
    function(0);
}

void function(int variable)
{
    variable = 0;
    cout << "alue of your variable after the process : " << variable << endl;
}
