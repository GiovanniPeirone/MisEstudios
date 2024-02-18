

En c++ la estructura básica es:

#include<iostream>


int main(){
	 std::cout << "helo World";
	return 0;
	}


pero si ponemos

#include<iostream>
using namespace std;

int main(){
	cout << "helo World";
	return 0;
}


Reducimos 
std::cout<<"hola mundo";  
a 
cout<<"hola mundo";



-------------------------------------------------------------------------------------------------------------


int main(){
	 //La aplicacion se ejecuta aqui
    return 0;
}


-------------------------------------------------------------------------------------------------------------


#include<iostream>

biblioteca estándar en C++ para poder tener acceso a los dispositivos estándar de entrada y/o salida.