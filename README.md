# artikyil
    import java.util.Scanner;

    public class Main {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int yıl;
        boolean artik = false;
        Scanner scanner = new Scanner(System.in);

        System.out.print("Yıl giriniz: ");
        yıl = scanner.nextInt();

        if (yıl % 4 == 0) {
            if (yıl % 100 == 0) {
                if (yıl % 400 == 0) {
                    artik = true;
                }
            } else {
                artik = true;
            }
        }
        if (artik) {
            System.out.println("Evet, artık yıl");
        } else {
            System.out.print("Hayır, artık yıl değil");
        }}
    }
