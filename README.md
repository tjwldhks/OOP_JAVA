
public class java {
	
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		for(int i=1; i<10; i++) {
			  for(int j = 0; j<=i; j++) {
			    System.out.print("#");
			  }
			  System.out.println("");
		}
		System.out.println("");
	
		for(int i=10; i>=1; i--) {
			for(int j = 0; j<i; j++) {
			    System.out.print("#");
			}
			System.out.println("");
		}
		System.out.print("");

		for(int i=1; i<=10; i++) {
			for(int j = 0; j<10 - i; j++) {
				System.out.print("");
			}
			for(int j = 0; j < i; j++) {
			    System.out.print("#");
			}
			System.out.println("");
		}
		System.out.println("");
	
		for(int i=10; i>=1; i--) {
			for(int j = 0; j<10 - i; j++) {
			    System.out.print("");
			}
			for(int j = 0; j < i; j++) {
			    System.out.print("#");
			}
			System.out.println("");
		}
	}
}
![Alt homework1](./images/images/스크린샷 2026-09-08 151035.png)

public class homework2 {
	
	public static void main(String[] args) {
		int n = 20;
		long[] fib = new long[n];
		fib[0] = 1;
		fib[1] = 1;
		for (int i = 2; i < n; i++) {
			fib[i] = fib[i - 1]+ fib[i - 2];
		}
		
		for (int i = 0; i < n; i++) {
			System.out.print(fib[i]);
			if(i != n -1) {
				System.out.print("");
			}
		}
		System.out.println();
	}
}

