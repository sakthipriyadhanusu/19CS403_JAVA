# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
To write a Java program that creates a StringBuilder object using a given string and assigns its reference to the variable sb.

## ALGORITHM :
1.	Start the program.
2.	Declare and initialize a string variable str1.
3.	Create a StringBuilder object by passing str1 to its constructor.
4.	Store the object reference in the variable sb.
5.	Print the contents of sb to verify the output.
6.	End the program.


## PROGRAM:
 ```
/*
Program to implement a StringBuilder Object Reference in Java
Developed by: SAKTHI PRIYA D
RegisterNumber: 212222040139 
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Main
{
    public static void main(String[]args)
  {
        Scanner scan = new Scanner(System.in);
        String name = scan.nextLine();
        StringTokenizer st = new StringTokenizer(name);
        System.out.println("Total number of Tokens: "+st.countTokens());
   }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/a79be09b-317d-4496-9b4c-34c3312ab014)


## RESULT:
Thus the  Java program successfully creates a StringBuilder object using the given string and stores the reference in the variable sb. The contents of the object are printed using the reference variable.

