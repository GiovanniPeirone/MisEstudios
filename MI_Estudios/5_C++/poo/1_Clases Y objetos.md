class MyClass {       // la clase  
    public:             // Specificacion de acceso
		int n;
  
 
};




int main() {  
  MyClass **myObj**;  // Create an object of MyClass  
  
  // Access attributes and set values  
  **myObj.n** = 15;   
 
  
  // Print attribute values  
  cout << myObj.myNum << "\n";  
  cout << myObj.myString;  
  return 0;  
}


