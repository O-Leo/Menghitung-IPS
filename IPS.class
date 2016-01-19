# Menghitung-IPS
Menghitung IP Semester
package ganjil.genap;

import java.util.Scanner;

/**
 *
 * @author O-Leo
 */
public class HitungIPS {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        String nama,matkul,d;
        char c;
        int a,sks = 0;
        double b,nilai,total = 0,akhir;
        System.out.println("Masukka Nama");
        nama = s.next();
        do{
            System.out.print("INPUT (N berhenti) ? : ");
            c = s.next().charAt(0);
            System.out.print("Masukkan Nama Matkul :");
            matkul = s.next();
            System.out.print("Input SKS :");
            a = s.nextInt();
            sks = sks + a;
            System.out.print("Masukkan Nilai :");
            d = s.next();
            switch(d){
                case "A" : 
                    b = 4;
                    break;
                case "AB":
                    b = 3.5;
                    break;
                case "B" :
                    b = 3;
                    break;
                case "BC":
                    b = 2.5;
                    break;
                case " C" :
                    b = 2;
                    break;
                    case "D" :
                    b =  1;
                    break;
    		case "E" :
                    b = 0;
                    break;
    		default :
                    b = -1;
                    break;
            }   
            nilai = a * b;
            total = total + nilai;
        }while (c != 'N');
        akhir = total / sks;
        System.out.println("Nilai anda "+akhir);
    }
}
