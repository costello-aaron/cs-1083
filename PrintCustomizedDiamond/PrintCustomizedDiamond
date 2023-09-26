import java.util.Scanner;
public class PrintCustomizedDiamond {

    public static void main(String[] args){
        Scanner scnr = new Scanner(System.in);
        System.out.print("Enter a letter: ");
        String character = scnr.nextLine();
        System.out.print("Enter a size (even number no less than 6): ");
        int size = scnr.nextInt();
        while (size % 2 != 0 || size < 6) {
            System.out.print("Enter a size (even number no less than 6): ");
            size = scnr.nextInt();
            continue;
        }
        System.out.println();
        for (int i = 2; i <= size; i += 2) {
            int spaces = (size - i) / 2;
            for (int j = 0; j < spaces; j++) {
                System.out.print(" ");
            }
            for (int j = 0; j < i; j++) {
                System.out.print(character);
            }
            System.out.println();
        }

        for (int i = size; i >= 2; i -= 2) {
            int spaces = (size - i) / 2;
            for (int j = 0; j < spaces; j++) {
                System.out.print(" ");
            }
            for (int j = 0; j < i; j++) {
                System.out.print(character);
            }
            System.out.println();
        }
    }
}
