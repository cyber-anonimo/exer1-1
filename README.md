# exer1-1
#include<iostream>
#include<cmath>
using namespace std;
//escopo global
int delta;

int bascara(){
	float a, b, c;

    cout << "Coeficiente a: ";
    cin >> a;

    cout << "Coeficiente b: ";
    cin >> b;

    cout << "Coeficiente c: ";
    cin >> c;

    if(a != 0){
        delta = sqrt(b) - (4*a*c);
        cout << delta;
	}else if(delta < 0){
		cout << "nao tem raiz";
	}
return 0;
}

int main(){
	//escopo de função
	bascara();
return 0;
}
