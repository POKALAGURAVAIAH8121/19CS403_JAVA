# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY
## AIM:
To create a java program that returns the sum of all the values in a 2D array.
## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `sum`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read `rows` and `cols` from user
-	c) Declare 2D array `arr[rows][cols]`
4.	Populate `arr` using nested loops with user input
5.	Initialize `sum` to `0`
6.	Calculate the sum of all elements in `arr` using nested loops
7.	Print "The sum of all values in the 2D array is: " + `sum`
8.	End
## PROGRAM:
 ```
/*
Program to implement a Multi Dimensional Array using Java
Developed by: POKALA GURAVAIAH
RegisterNumber: 212222040114
*/
```
## Sourcecode.java:
```
import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);

        int rows = scan.nextInt();
        int cols = scan.nextInt();

        int[][] arr = new int[rows][cols];

        for (int i = 0; i < rows; i++) {
            for (int j = 0; j < cols; j++) {
                arr[i][j] = scan.nextInt();
            }
        }

        int sum = 0;
        for (int i = 0; i < rows; i++) {
            for (int j = 0; j < cols; j++) {
                sum += arr[i][j];
            }
        }

        System.out.println("The sum of all values in the 2D array is: " + sum);
    }
}
```
## OUTPUT:
<img width="400" alt="image" src="https://github.com/user-attachments/assets/de07dd58-9823-4386-a4ee-d8df76ab9b65"/>

## RESULT:
Thus the java program that returns the sum of all the values in a 2D array was executed successfully.


