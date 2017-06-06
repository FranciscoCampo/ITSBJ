package encuesta;
import java.util.Scanner;
public class multiploopcional{
    
 public static void main ( String [] args ) {
     
     Scanner scan = new Scanner ( System.in );
     
     String resultado="";
     
     System.out.println("Ingrese el numero del Multiplo que desea saber: ");
     int n = scan.nextInt();
     
     System.out.println("los multiplos de: " +  n  +  "   Desde 0 hasta:   ");
     int fin=scan.nextInt();
     
     
     for (int i= 1; i < fin ; i++){
        if(i%n==0){
         resultado= resultado+i+"\n";
        }   
     }
     System.out.println("Resultado: ");
      System.out.println(resultado);
     
 }  
    
}
