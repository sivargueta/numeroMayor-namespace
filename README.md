# numeroMayor-namespace

#include <stdio.h>
#include <iostream>
using namespace std;

int main()
{
    int a, b;
    
    cout<<"Ingrese un numero:";
    cin >> a;
    
    cout<<"Ingrese otro numero:";
    cin >>b;
    
    if (a>b) {
        cout <<"a es mayor" <<endl;
        
    }else{
        cout <<"b es mayor" <<endl;
        
    }

    return 0;
}
