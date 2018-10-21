# mayor-de-3-numeros

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package mayor.de.pkg3.numeros;

import java.util.Scanner;

/**
 *
 * @author Adolf
 */
public class MayorDe3Numeros {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        Scanner sc=new Scanner(System.in);
        System.out.println("Ingresar 1er. Numero ");
        int A = sc.nextInt();
        System.out.println("Ingresar 2do. Numero ");
        int B = sc.nextInt();
        System.out.println("Ingresar 3er. Numero ");
        int C = sc.nextInt();
        
        
        if(A>B&&A>C){
            System.out.println("El Numero Mayor es " +A);
        }else{
            if(B>A&&B>C){
                System.out.println("El Nuemro mayor es " +B);
                }else{
                System.out.println("El Numero mayor es " +C);
            }
        }
    }
    
}
