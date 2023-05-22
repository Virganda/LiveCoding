/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */

package W4;

import java.util.Scanner;

/**
 *
 * @author VIRGANDA R A
 * 22104410010
 */
public class MainKinetic {
 
    public double massa;
    public double kecepatan;




    public double getMassa() {
        return massa;
    }

    public void setMassa(double massa) {
        this.massa = massa;
    }

    public double getKecepatan() {
        return kecepatan;
    }

    public void setKecepatan(double kecepatan) {
        this.kecepatan = kecepatan;
    }
    
    public double EK(){
        double hasil = 0.5 * massa * Math.pow(kecepatan, 2);
        return hasil;
    }
    
    public static void main(String[] args) {
        MainKinetic V = new MainKinetic();
        
       Scanner scanner = new Scanner(System.in);
        System.out.println("Masukkan Massa: ");
        V.setMassa(scanner.nextDouble());
        
        System.out.println("Masukkan Kecepatan : ");
        V.setKecepatan(scanner.nextDouble());
        
        V.getMassa();
        V.getKecepatan();
        System.out.println("Massa adalah " + V.massa);
        System.out.println("kecepatan adalah "+ V.kecepatan);
        System.out.println("Hasil : " +V.EK());
    }
    
}
