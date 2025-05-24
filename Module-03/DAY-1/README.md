# Ex.No:3(A)  STRING AND ITS OPERATIONS IN JAVA
## AIM:
To create a java program to read input and print length of the string in java.

## ALGORITHM :
1.  Start the Program.
2.	Import `Scanner` and define class `demo`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read a line of text into `String` variable `str`
4.	Print "The size of the String is " + `str.length()`
5.	End




## PROGRAM:
 ```
/*
Program to implement a String and its Operations using Java
Developed by: POKALA GURAVAIAH
RegisterNumber:  212222040114
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

public class Demo {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter a string:");
        String str = sc.nextLine();
        System.out.println("The size of the String is " + str.length());
    }
}
```

## OUTPUT:
```
Input                      Output

Enter a string:            The size of the String is 3
abc                        
```



## RESULT:
Thus the java Program to read input and print length of the string in java was executed successfully.

