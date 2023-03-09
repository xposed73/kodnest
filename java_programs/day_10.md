### Write a Java program to read the first name of the user also display the name.

```java
import java.util.*;

class Program {
	public static void main(String[] args) {
		
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter your first name ");
		
		String name = sc.next();
		System.out.println("The name of user is: " + name);
		
	}
}
```
