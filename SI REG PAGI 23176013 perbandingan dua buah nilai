/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package javaapplication2;

import java.util.Scanner;

/**
 *
 * @author NITRO V 15
 */
public class tugas8 {
 
    public static void main(String[] args) {
        try (Scanner scanner = new Scanner(System.in)) {
            String ulangi;
            
            do {
                System.out.println("========Program Perbandingan Nilai========");
                System.out.print("Masukkan nilai pertama : ");
                int nilaiPertama = scanner.nextInt();
                System.out.print("Masukkan nilai kedua : ");
                int nilaiKedua = scanner.nextInt();
                
                if (nilaiPertama > nilaiKedua) {
                    System.out.println("Hasil : " + nilaiPertama + " Lebih besar dari " + nilaiKedua);
                } else if (nilaiPertama < nilaiKedua) {
                    System.out.println("Hasil : " + nilaiPertama + " Lebih kecil dari " + nilaiKedua);
                } else {
                    System.out.println("Hasil : " + nilaiPertama + " Sama dengan " + nilaiKedua);
                }
                
                System.out.print("\nUlangi Aktifitas ? (Ya/Tidak) : ");
                ulangi = scanner.next();
            } while (ulangi.equalsIgnoreCase("Ya"));
        }
    }
}


