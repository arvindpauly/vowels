# vowels
import java.util.Scanner;

public class Juspay4 {
	public static void main(String[] args) {
		Scanner a = new Scanner(System.in);
		int count = 0;
		System.out.println("enter the String");
		String s1 = a.next();
		a.close();
		s1 = s1.toLowerCase();

		for (int i = 0; i < s1.length(); i++) {
			if (s1.charAt(i) == 'a' || s1.charAt(i) == 'e'
					|| s1.charAt(i) == 'i' || s1.charAt(i) == 'o'
					|| s1.charAt(i) == 'u') {
				count++;
			}
		}
		System.out.println(count);
	}
}
