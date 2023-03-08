# Implicit & Explicit typecasting

### Program1 for implicit typecasting
```java
class ProgramImplicitTypecasting{

  public static void main (String args[]){
    
    byte a = 45;
    int b;
    
    b = a;
    System.out.println(a); // Prints "45"
    System.out.println(b); // Prints "45"
    
  }

}
```

### Program2 for implicit typecasting
```java
class ProgramImplicitTypecasting{

  public static void main (String args[]){
    
    int a = 73;
    double b;
    
    b = a;
    System.out.println(a); // Prints "73"
    System.out.println(b); // Prints "73.0"
    
  } 

}
```

### Program1 for explicit typecasting
```java
class ProgramExplicitTypecasting{

  public static void main (String args[]){
    
    int a = 56;
    short b;
    
    //b = a; (Thros error)
    b = (short)a;
    System.out.println(a); // Prints "56"
    System.out.println(b); // Prints "56"
    
  }

}
```
### Program2 for explicit typecasting
```java
class ProgramExplicitTypecasting{

  public static void main (String args[]){
    
    double a = 49.72;
    int b;
    
    //b = a; (Thros error)
    b = (int)a;
    System.out.println(a); // Prints "49.72"
    System.out.println(b); // Prints "49" (Here we can see, data loss has happend)
    
  }

}
```

## Extended example
### Write a java program to calculate the area of a square.

```java
class Program {

  public static void main (String args[]){
  
    float width = 10F;
    float result = width * width;
    
    System.out.println("The area of square is: " + result); // The area of square is: 100.0
  
  }

}
```

### Write a java program to calculate the area of a circle.
```java
class Program {

  public static void main (String args[]){
  
    float radius = 20F;
    float pi = 3.141592653589793238F;
    float result = 2*pi*radius;
    
    System.out.println("The area of circle is: " + result);
  
  }

}
```
