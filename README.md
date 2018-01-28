# Szaraczki
#include <iostream>
#include <conio.h>
#include <math.h>

using namespace std;
int main()

{
    
    float a;
    float b;
    float c;
    float d;
   
    cout << "Podaj A" << endl;
    cin >> a;
    cout << "Podaj B" << endl;
    cin >> b;
    cout << "Podaj C" << endl;
    cin >> c;

     d = b*b - 4*a*c;

    If(d>0)
    {
        cout << "x1=" << (-b - sqrt(d))/2*a; << endl;
        cout << "x2=" << (-b + sqrt(d))/2*a; << endl;
    }

    If(d==0)
    {
        cout << "x=" << -b/2*a << endl;
    }

    If(d<0)
    {
        cout << "Brak Pierwiastków!" <<endl;
    }

    getch();
    return 0;
}
