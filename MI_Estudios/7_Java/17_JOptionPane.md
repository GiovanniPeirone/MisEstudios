

JOptionPane Es una libreria que crea ventanas emerjentes 


import javax.swing.JOptionPane; //Libreria

public class PelonesRPG {

    
    public static void main(String[] args) {
        
        //PEDIR STRING
        
        String Cadena;//Variable String
        Cadena = JOptionPane.showInputDialog("Dijite un string");//Pedir Variable string
        
        
        
        
        //PEDIR ENTERO
        
        int Entero; //Define Una variable int
        Entero = Integer.parseInt(JOptionPane.showInputDialog("Dijite un Entero: "));//                                                                       Pedir la variable int
        
        /*
        * El: Integer.parseInt Comvierte el int en string
        */
        
        
        //PEDIR LETRA
        
        char Letra; //Define un char
        Letra = JOptionPane.showInputDialog("Dijite una letra: ").charAt(0);//Pide la                                                                                    letra
        
        /*
        * El: .charAt(0) Comvierte el char a string
        */
        
        
        //PEDIR DECIMAL
        
        double Decimal;//Define double o float 
        Decimal = Double.parseDouble(JOptionPane.showInputDialog("Dijite un decimal:"));                                                                          //Pide el decimal
        
        /*
        * El: Double.parseDouble  Comvierte el Decimal en string  Tabien se pueda                   camviar para float
        */
        
		   //MOSTRARLOS
        
        
        JOptionPane.showMessageDialog(null, "La cadena es: "+Cadena);// Muetra la cadena
        JOptionPane.showMessageDialog(null, "El entero es: "+Entero );//Muestra el                                                                                 entero
        JOptionPane.showMessageDialog(null, "La letra es: "+Letra);//Muetra la letra
        JOptionPane.showMessageDialog(null, "El decimal es:"+Decimal);//muestra El                                                                               decimal
    }
    
}



Video: https://youtu.be/VFAG5uedkm4?si=Osk9oyjrlGIiODmn


