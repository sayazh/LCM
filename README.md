# LCM
Lowest Common Multiple
package Assignments2;

import java.util.Scanner;

public class lowestCommonMultiple {

	public static void main(String[] args) {

		System.out.println("Enter two numbers");
		Scanner sc = new Scanner(System.in);
		int number1 = sc.nextInt();
		int number2 = sc.nextInt();
		int result;
		for (result = number1; true; result++) {
			if (result % number1 == 0 && result % number2 == 0) {
				break;
			}
		}
		System.out.println("Lower Common Multiple = " + result);

		sc.close();
	}

}
