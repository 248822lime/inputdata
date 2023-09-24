# inputdata
package inputdata.Inputdata;
import java.util.Scanner;
public class Main {

    public static void main(String[] args) {
        Scanner input = new Scanner (System.in);
        String nama, alamat;
        int usia;
        
        System.out.println("Masukan Data Anda :");
        System.out.print("Nama \t: ");
        nama = input.nextLine();
        System.out.print("Alamat \t: ");
        alamat = input.nextLine();
        System.out.print("Usia \t: ");
        usia = input.nextInt();    
    }   
}
