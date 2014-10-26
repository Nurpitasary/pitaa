pitaa
=====

TugasPercabangan

import java.util.Scanner;

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
/** 
 *
 * @author USER
 */
public class TugasPraktek3 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here 
        Scanner input = new Scanner (System.in);
       //perulangan while
        int p = 0;
        while(p<5) {
            System.out.println("nilai p : "+p);
            p++;
        }
        
        //percabangan
        int nilaiKelas = input.nextInt();
        if ( nilaiKelas >= 85 )
            
        {System.out.println("A");} else if ( nilaiKelas >= 75)
        {System.out.println("B");} else if ( nilaiKelas >= 65)
        {System.out.println("C");}  else if ( nilaiKelas >= 55)
        {System.out.println("D");} else {System.out.println("E");
       
                }}}
               
