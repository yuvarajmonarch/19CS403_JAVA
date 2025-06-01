# Ex.No:1(A) CLASS & OBJECTS

## AIM:

To create a class named 'Student' with String variable 'name' and String variable 'address'.

## ALGORITHM :

1. Start the program.
2. Define a class named 'Student'
3. Declare a String variable 'name' and initialize it with the value "John"
4. Declare a String variable 'address' and initialize it with the value "Chennai"
5. Define a class named 'Test'
6. Define the 'main' method within the 'Test' class
7. Create an object 'obj' of the 'Student' class
8. Print the value of 'name' and 'address' variables of the 'obj' object
9. End

## PROGRAM:

```
/*
Program to implement a class & objects using Java
Developed by: YUVARAJ B
RegisterNumber:  212222040186
*/
```

## Sourcecode.java:

```Python
public class Student
{
    String name,address;
    int rollno;
}
public class Main {
    public static void main(String[] args) {
        Student obj= new Student();
        obj.name="John";
        obj.address="Chennai";
        obj.rollno=10;
        System.out.println(obj.name+" "+obj.address+" "+obj.rollno);
    }
}

```

## OUTPUT:

![image](https://github.com/user-attachments/assets/6a1d94a9-2b17-44b9-86ca-f9befceba5ad)

## RESULT:

Thus, the class named 'Student' with String variable 'name' and String variable 'address' was created successfully.
