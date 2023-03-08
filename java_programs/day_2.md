### Addition of two numbers
```java
class Program {

  public static void main (String args[]){
  
    int a = 20;
    int b = 10;
    int sum = a+b;
    
    System.out.println("The addition is "+ sum);
  
  }

}
```

### Program for Increment
```java
class Program {

  public static void main (String args[]){
  
    int a = 5;   
    System.out.println(a); //5

    ++a;
    System.out.println(a); //6
  
  }

}
```

### Program for Decrement
```java
class Program {

  public static void main (String args[]){
  
    int a = 5;   
    System.out.println(a); //5

    --a;
    System.out.println(a); //4
  
  }

}
```

### Extended example
```java
class Program {

  public static void main (String args[]){
  
    int a = 5;   
    System.out.println(a); //Prints 5
    
    int b = ++a + ++a + a++ + --a + a-- + ++a + a--;
    System.out.println(b); //Prints 48
   
  }

}
```
