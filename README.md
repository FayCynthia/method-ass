@@ -0,0 +1,30 @@
import java.util.Scanner;
public class Methods {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Asking the user to enter three numbers
        System.out.println("Enter three numbers: ");
        int num1 = scanner.nextInt();
        int num2 = scanner.nextInt();
        int num3 = scanner.nextInt();

        // Finding the largest and smallest numbers
        int smallest = findSmallest(num1, num2, num3);
        int largest = findLargest(num1, num2, num3);

        // Displaying the results
        System.out.println("The smallest number: " + smallest);
        System.out.println("The largest number: " + largest);
        System.out.println(largest + " is your largest and " + smallest + " smallest number.");
    }
