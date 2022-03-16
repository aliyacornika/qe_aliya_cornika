# Problem 1 Jam Pasir
import java.util.Scanner;

public class jampasir {
    public static void main(String[] args) {

        System.out.println("masukkan jumlah bintang: ");
        Scanner scan = new Scanner(System.in);
        int jmlbintang = scan.nextInt();

        for(int i=jmlbintang;i>0;i--) {
            for(int j=jmlbintang-i;j>=1;j--) {
            
                System.out.print(" ");
            }

            for(int j=1;j<=i;j++) {

                System.out.print("* ");
                
            }
            
            System.out.println();
        }

        for(int i=1;i<=jmlbintang;i++) {

            for(int j=1;j<=jmlbintang-i;j++) {

                System.out.print(" ");

            }

            for(int j=1;j<=i;j++) {

                System.out.print("* ");
            }
            
            System.out.println();
        }
    }
}

# Problem 2 Suku Kata O
import java.util.Scanner;
public class SukuKata {

        Scanner scan = new Scanner(System.in);
        String sukuKata = scan.nextLine();

        public static void englishToMorse(String[] code,
                                          String sukukata,
                                          char[] letter)
        {
            System.out.print("Morse code of " + sukukata
                    + " is ");
            for (int i = 0; i < sukukata.length(); i++) {
                for (int j = 0; j < letter.length; j++) {
                    if (sukukata.charAt(i) == letter[j]) {
                        System.out.print(code[j] + " ");
                        break;
                    }
                }
            }
        }

        public static void main(String[] args)
        {


            char[] letter = { 'a', 'b', 'c', 'd', 'e', 'f',
                    'g', 'h', 'i', 'j', 'k', 'l',
                    'm', 'n', 'o', 'p', 'q', 'r',
                    's', 't', 'u', 'v', 'w', 'x',
                    'y', 'z', ;

# Problem 3 Muatan OOP
Public class Hewan {
    int berat;
}

public class Mobil {
    int kapasitas;
    String muatan;

    void tambahMuatan()

}

# Problem 4 Index Huruf
public class index {
public static int PosisiIndex(int[][]arr, int x){
    for (int i = 0; i<arr.length;i++){
    if (arr[i] == x)
    return i;
}
    return -1;
}

public class main {
    public static void main(String[] args){
        char[][]table = {"","","","","",""};
                        {"","A","B","C"/"K","D","E"};
                        {"","F","G","H","I","J"};
                        {"","L","M","N","O","P"};
                        {"","Q","R","S","T","U"};
                        {"","V","W","X","Y","Z"};
        
    }
}
}

