## Classes & Objects in Java

### Class File
```java
class Student {
     int roll_no = 73;
     String name = "Xposed";
     int age = 25;
     
   void study(){
     System.out.println("Student is studying...");
   }
   
   void doCoding(){
     System.out.println("Student is coding...");
   }
}
```

### Ceating an object (instance of a class)
```java
Student s1 = new Student();
s1.study(); //Prints "Student is studying..."
```


## EXTENDED EXAMPLE

### Class Laptop.java
```java
class Laptop {

     String brand;
     String color;
     int cost;
     
    void switchOn(){
      System.out.println("Laptop is switched on")
    }
    
    void switchOn(){
      System.out.println("Laptop is working...")
    }
    
    void switchOn(){
      System.out.println("Laptop is switched off !!!")
    }

}
```
### Class MyLaptop.java
```java
class MyLaptop{
     
     public ststic void main (String args[]){
     
      Laptop laptop1 = new Laptop();
      Laptop laptop2 = new Laptop();
      
      //Laptop 1
      laptop1.brand = "Dell";
      laptop1.processor = "i7";
      laptop1.cost = 70000;
     
      //Laptop 2
      laptop2.brand = "Apple";
      laptop2.processor = "M2";
      laptop2.cost = 200000;
      
      //Laptop 1
      laptop1.switchOn(); // Prints "Laptop is switched on"
      laptop1.switchOff(); // Prints "Laptop is switched off !!!"
      
      //Laptop 2
      laptop1.switchOn(); // Prints "Laptop is switched on"
      laptop1.work(); // Prints "Laptop is working..."
      laptop1.switchOff(); // Prints "Laptop is switched off !!!"
     
     }

}
```
