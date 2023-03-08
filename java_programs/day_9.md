# Usage of Scanner utility in Java
### Write a java program to find square of a number by taking the input from user.

```java
import java.util.Scanner; // Import Scanner utility

class Program {

	public static void main (String args[]){
		
		System.out.println("Enter a number: ");
		Scanner scan = new Scanner(System.in);
		
		int a = scan.nextInt();
		int result = a * a;

		System.out.println("The square of number is: " + result);
	
	}

}
```

```java
Scanner sc = new Scanner(System.in);

byte a = sc.nextByte(); //To take input as byte
short b = sc.nextShort(); //To take input as short
int c = sc.nextInt(); //To take input as int
long d = sc.nextLong(); //To take input as long
float e = sc.nextFloat(); //To take input as float
```
