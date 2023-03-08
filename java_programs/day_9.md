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

### Scanner usage for other data types
```java
Scanner sc = new Scanner(System.in);

byte a = sc.nextByte(); //To take input as byte
short b = sc.nextShort(); //To take input as short
int c = sc.nextInt(); //To take input as int
long d = sc.nextLong(); //To take input as long
float e = sc.nextFloat(); //To take input as float

String f = sc.nextLine(); //To take input as string
char g = sc.next().charAt(0); //To take input as character
 
```

### Write a java program to create a calculator which will perform addition, subtraction, multiplication and division also take the user input from the keyboard.

### Calculator.class
```java
class Calculator {

	int a, b, result;
	
	void add(){
	    result = a + b;
	    System.out.println("The addition of two numbers is: "result);
	}
	
	void sub(){
	    result = a - b;
	    System.out.println("The subtraction of two numbers is: "result);
	}
	
	void mul(){
	    result = a * b;
	    System.out.println("The multiplication of two numbers is: "result);
	}
	
	void div(){
	    result = a / b;
	    System.out.println("The division of two numbers is: "result);
	}

}
```
