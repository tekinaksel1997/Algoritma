package CalısmaSoruları;
import java.util.Scanner;
public class Soru24 {
	public static void main(String[] args) {
		System.out.print("Bir sayi giriniz : ");
    	Scanner scan = new Scanner(System.in); 
        int sayi = scan.nextInt(); 
        int i = 0;
        int j[] = new int[20];
        while(sayi >= 1){
            i++;
            j[i] = sayi%2;
            sayi = sayi / 2;
        }   
        System.out.print("İkilik sistem -> ");
         
        while(i > 0){
            System.out.print(j[i]);
            i--;
        }
	}
}
