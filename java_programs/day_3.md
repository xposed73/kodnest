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
