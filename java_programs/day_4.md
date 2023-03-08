### Create a calculator application to do
### four opn's (ADD, SUB, MUL, DIV)

### Calculator.java
```java
class Calculator {

  int a = 10;
  int b = 5;
  int result;

  void add() {
    result = a + b;
    System.out.println("The addition of two numbers is: " + result)
  }

  void sub() {
    result = a - b;
    System.out.println("The subtraction of two numbers is: " + result)
  }

  void mul() {
    result = a * b;
    System.out.println("The multiplication of two numbers is: " + result)
  }

  void div() {
    result = a / b;
    System.out.println("The division of two numbers is: " + result)
  }

}
```

### MyCalculator.java
```java
class MyCalculator {

  public static void main (String args[]){
  
  Calculator c1 = new Calculator();
  
  }
  
}

