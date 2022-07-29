# y-ld-z-kristal-yap-m-
Java'da döngüler kullanılarak yıldızlar ile üçgen yapıyoruz.

    import java.util.Scanner;

     public class Main {
    public static void main(String[] args) {
        Scanner klavye = new Scanner(System.in);
        System.out.print("Bir Sayı Giriniz :");
        int n = klavye.nextInt();

        for (int i = 1; i <= n; i++) {

            for (int j = 0; j <= (n - i); j++) {
                System.out.print(" ");
            }

            for (int k = 1; k <= (2 * i) - 1; k++) {
                System.out.print("*");
            }
            System.out.println();
        }
        for (int i = 0; i <= n; i++) {

            for (int j = n; j >= (n - i); j--) {
                System.out.print(" ");
            }
            for (int k = 1; k <= (2 * (n - i) - 1) ; k++) {
                System.out.print("*");
            }

            System.out.println();
        }
       }
     }
     

  https://app.patika.dev/ahmetfurkan
  
  ![image](https://user-images.githubusercontent.com/107626332/181746335-c0ca14e1-b92d-4652-9699-5bba2c39bbb0.png)
