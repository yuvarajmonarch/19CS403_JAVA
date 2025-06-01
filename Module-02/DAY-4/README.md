# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:

To create a java program that returns the sum of all the values in a 2D array.

## ALGORITHM :

1. Start the program.
2. Import `Scanner` and define class `sum`
3. In `main`:

- a) Create `Scanner` object `sc`
- b) Read `rows` and `cols` from user
- c) Declare 2D array `arr[rows][cols]`

4. Populate `arr` using nested loops with user input
5. Initialize `sum` to `0`
6. Calculate the sum of all elements in `arr` using nested loops
7. Print "The sum of all values in the 2D array is: " + `sum`
8. End

## PROGRAM:

```
/*
Program to implement a class & objects using Java
Developed by: YUVARAJ B
RegisterNumber:  212222040186
*/
```

## Sourcecode.java:

```
import java.util.*;
public class Main{
    public static void main(String[] args)
    {
        Scanner in = new Scanner (System.in);
        int rows=in.nextInt();
        int cols=in.nextInt();
        int[][] arr=new int[rows][cols];
        int sum = 0;
        int i,j;
        for(i=0;i<rows;i++)
        {
            for(j=0;j<cols;j++){
                arr[i][j]=in.nextInt();
                sum+=arr[i][j];}
        }
        System.out.print("The sum of all values in the 2D array is: "+sum);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/1336adb2-ec70-4054-b56f-08efacf8267b)

## RESULT:

Thus the java program that returns the sum of all the values in a 2D array was executed successfully.
