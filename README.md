# ch5
import java.util.Scanner;

public class StringSearch { public static void main(String[] args) { Scanner scanner = new Scanner(System.in); System.out.print("Enter the first string: "); String str1 = scanner.nextLine(); System.out.print("Enter the second string: "); String str2 = scanner.nextLine(); scanner.close();

    if (str1.contains(str2)) {
        System.out.println(str2 + " is found in " + str1);
    } else {
        System.out.println(str2 + " is not found in " + str1);
    }
}
}
