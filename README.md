# the-first-program
#include <iostream>
using namespace std;
int main()
{
    double number  , factorial = 1;
    cout << "please enter the number \a \n";
    cin >> number ;
    if (number <=0 || number >=100 )
        cout << "please enter the number from 1 to 100 \a \n";
    else
        for (int i = 1 ; i <= number ; i++ )
    {
        factorial = factorial * i;
    }
    cout << "the factorial number = \a" << factorial << "\n";


}

