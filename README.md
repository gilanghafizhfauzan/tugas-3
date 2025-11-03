# tugas-3
import java.util.Scanner;

public class Faktorial {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Masukkan bilangan bulat positif: ");
        int n = input.nextInt();

        if (n < 0) {
            System.out.println("Bilangan harus positif!");
        } else {
            long faktorial = 1; // Gunakan long untuk menangani bilangan besar
            for (int i = 1; i <= n; i++) {
            
                faktorial *= i;
            }
            System.out.println("Faktorial dari " + n + " adalah " + faktorial);
        }

        input.close();
    }
}
Potongan kode ini digunakan untuk **menghitung faktorial** dari sebuah bilangan bulat positif:

1. Program meminta input bilangan `n`.
2. Jika `n < 0`, program menampilkan pesan **"Bilangan harus positif!"**.
3. Jika tidak, program menghitung faktorial dengan perulangan `for` dari 1 sampai `n`, menyimpan hasilnya di variabel `faktorial`.
4. Setelah selesai, hasil faktorial ditampilkan ke layar.
5. Scanner ditutup dengan `input.close()`.

