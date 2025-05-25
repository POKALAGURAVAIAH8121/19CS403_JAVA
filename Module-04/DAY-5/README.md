# Ex.No:4(E)  PARAMETERIZED CONSTRUCTOR
## AIM:
To write a parameterized constructor in the Employee class that initializes name and designation, and then call getter methods in the main() method of another class (Sample) to display the values.

## ALGORITHM :

	1.	Start the program.

2.	Define a class Employee:
3.	
    a.	  Declare two private string variables: name and designation.
  	
5.	Create a parameterized constructor in Employee:

6.	Accept two parameters: name and designation.
8.	Assign the parameters to the class fields.
9.	Define two getter methods in the Employee class:
     a.	getName() – returns the value of name.
     b.	getDesg() – returns the value of designation.
10.	Create another class Sample with the main method.
11.	Inside the main method:
     a.	Create an object of Employee using the constructor and pass "John" and "Asst.Manager" as arguments.
     b.	Call getName() and store the result in a variable empName.
     c.	Call getDesg() and store the result in a variable empDesg.
12.	Print the values of empName and empDesg.
13.	End the program


## PROGRAM:
 ```
/*
Program to implement a Parameterized Constructor Using Java
Developed by: POKALA GURAVAIAH
RegisterNumber:  212222040114
*/
```

## Sourcecode.java:

```
class Laptop {
    String brand;
    double price;
    public Laptop() {
        this.brand = "Apple";
        this.price = 42500.75;
    }

    public String getBrand() {
        return brand;
    }

    public double getPrice() {
        return price;
    }
}
public class Sample {
    public static void main(String[] args) {
        Laptop myLaptop = new Laptop();
        String laptopBrand = myLaptop.getBrand();
        System.out.println(laptopBrand);
        double laptopPrice = myLaptop.getPrice();
        System.out.println(laptopPrice);
    }
}
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/dd258499-d8e9-427a-97a0-9157d4055a30)


## RESULT:
Thus, the  java program was successfully parameterized constructor in the Laptop class given below that initializes the brand , price class field with the string "Apple" and 42500.75.

 


