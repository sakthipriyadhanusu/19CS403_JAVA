# Ex.No:1(C) CONTROL STATEMENTS

## AIM:
To develop a Java program to check given number is zero or not.

## ALGORITHM :
1.	Start the program.
2.	Declare an integer variable 'num'
3.	Create a Scanner object 'sc' to read input from the user
4.	Read an integer input from the user and store it in 'num'
5.	Check if 'num' is equal to 0:
a.	If true, print "Given number is Zero"
b.	If false, print 'num' followed by " is Non-Zero"
6.	End
7.	
## PROGRAM:
 ```
/*
Program to implement a class & objects using Java
Developed by: SAKTHI PRIYA D
RegisterNumber: 212222040139
*/
```

## Sourcecode.java:
```
import java.util.Scanner;
public class Demo {

    
  public static void main(String[] args)
    {
	   Scanner in = new Scanner(System.in);
       int num = in.nextInt();
       String Name = "";
       switch (num) {
           case 1: Name = "a"; break;
           case 2: Name = "e"; break;
           case 3: Name = "i"; break;
           case 4: Name = "o"; break;
           case 5: Name = "u"; break;
           default:Name = "Invalid range";
       }

      System.out.println(Name);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/51817f68-9b75-4e4a-a514-223398b0df3e)


## RESULT:
Thus, the Java program to check given number is zero or not was created successfully.

