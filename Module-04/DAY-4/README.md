# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
   To create a Java program to perform final & static keyword for below situation Employee object contains member 'Emp_Id'. It contains object named name, which contains its own informations such as Fname, Mname, Lname.
 
## ALGORITHM :
1.	Start the Program.
2.	Define class `Name`:
-	a) Declare three `String` variables: `Fname`, `Mname`, and `Lname`
-	b) Define method `dispName(String fn, String mn, String ln)`:
-	i) Print the full name using the passed parameters `fn`, `mn`, and `ln`
3.	Define class `Employee`:
-	a) Declare an integer variable `Emp_Id`
-	b) Create an instance of `Name` called `obj`
-	c) Define method `disp(int id)`:
-	i) Print the employee ID
-	ii) Create a new `Name` object and call `dispName("B", "Leo", "John")` to display the name
4.	Define `Main` class with `main` method:
-	a) Create an `Employee` object `emp`
-	b) Call `emp.disp(101)` to display the employee details
5.	End






## PROGRAM:
 ```
/*
Program to implement a final & Static using Java
Developed by: POKALA GURAVAIAH
RegisterNumber:  212222040114
*/
```

## Sourcecode.java:

```
class Subject {
    String subject1, subject2, subject3, subject4;

    void dispSub(String s1, String s2, String s3, String s4) {
        subject1 = s1;
        subject2 = s2;
        subject3 = s3;
        subject4 = s4;
        System.out.println(subject1 + " " + subject2 + " " + subject3 + " " + subject4);
    }
}

class Student {
    int Stu_Id;
    Subject sub = new Subject();

    void disp(int id, String s1, String s2, String s3, String s4) {
        Stu_Id = id;
        System.out.println(Stu_Id);
        sub.dispSub(s1, s2, s3, s4);
    }
}

public class Main {
    public static void main(String[] args) {
        Student st = new Student();
        st.disp(101, "Java", "DS", "TOC", "CG");
    }
}
```






## OUTPUT:
![image](https://github.com/user-attachments/assets/70c0a76a-f3e3-49f4-9590-84e1f38706ef)


## RESULT:
Thus, the java program for below situation, Student object contains member 'Stu_Id'. It contains  object named subject, which contains its own informations such as subject1,subject2,subject3,subject was executed successfully.
