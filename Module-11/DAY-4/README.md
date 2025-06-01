# Ex.No:11(D) RELATED TO MAP CONCEPTS

## AIM:

To Create a java program to insert and display the key and values using map interface.

## ALGORITHM :

1. Start
2. Import `java.util.*`
3. Define class `Deivamagal` with `main` method:

- a) Read integer `n` (number of entries).
- b) Create a `HashMap` `hash`.

4. Loop to read key-value pairs and add to `hash`.
5. Print `"Map: " + hash`, keys, values, and entries.
6. End

## PROGRAM:

```
/*
Program to implement a RELATED TO MAP CONCEPTS using Java
Developed by: YUVARAJ B
RegisterNumber: 212222040186
*/
```

## Sourcecode.java:

```
import java.util.*;
public class Mapp{
 public static void main(String args[]){

  Map<Integer,String> numbers=new HashMap<Integer,String>();
  Scanner sc=new Scanner(System.in);

  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  numbers.put(a,b);
  }

 System.out.println("Map: " + numbers);


        System.out.println("Keys: " + numbers.keySet());


        System.out.println("Values: " + numbers.values());


        System.out.println("Entries: " + numbers.entrySet());


 }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/8017c5f4-1ccd-4101-9194-177ac1176358)

## RESULT:

Thus the java program to insert and display the key and values using map interface was executed and verified successfully.
