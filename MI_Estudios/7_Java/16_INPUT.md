

NUMEROS
-------------------------------------------------------------------------------------------------------------

package clasesYobjetos;

import java.util.Scanner; //Libreria para INPUT

 public class Auto {
   
    public static void main(String [] args){
 
        Scanner n = new Scanner(System.in); //Crea el objero scaner
        int numero;
        System.out.print("Dijite un numero: ");
        numero = n.nextInt(); //Conado que pude el numero
        /*
        *  nextInt() varia segun el tipo de dato qu se la variable de numero 
        *  Ej : float numero;
                numero = n.nextFloat();   EN el imput los float se escriven con coma                                                no con punto 1,5 bien 1.5 mal
        */
        System.out.println("El numero es: "+numero);
    }
}



CADENAS DE TEXTO
-------------------------------------------------------------------------------------------------------------


      package clasesYobjetos;

      import java.util.Scanner; //Libreria para INPUT

public class Auto {
   
    public static void main(String [] args){
 
        Scanner n = new Scanner(System.in); //Crea el objero scaner
        String cadena;
        System.out.print("Dijite un numero: ");
        cadena = n.nextLine(); //Conado que pude el Texto 
        /*
        *  Para las cadenas tambien se puede poner solo next(); y guarda solo eltexto                haste que all un espacio
        *  Ej : String numero;
                cadena; = n.next(); EN caso de colocar hola mundo Solo va a guardar el                                         hola
        */
        System.out.println("El numero es: "+cadena); // Imprime L que se escribio
    }
}


CARACTERES
-------------------------------------------------------------------------------------------------------------


package clasesYobjetos;

import java.util.Scanner; //Libreria para INPUT

public class Auto {
   
    public static void main(String [] args){
 
        Scanner n = new Scanner(System.in); //Crea el objero scaner
        char letra;
        System.out.print("Dijite una letra: ");
        letra = n.next().charAt(0); // lee el caracter
        /*
        *  El charat(0); hace que solo lea la primera letra
        *  Ej : char letra;
                letra = n.next().charAt(0); EN caso de colocar HOLA Solo va a guardar                                                 la H
        */
        System.out.println("El numero es: "+letra); // Imprime Lo que se escribio
    }
}

