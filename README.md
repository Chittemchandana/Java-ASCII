# Java-ASCII
# How to Print ASCII Value in Java
public class PrintAsciiValueExample1   
{  
public static void main(String[] args)   
{  
// character whose ASCII value to be found  
char ch1 = 'a';  
char ch2 = 'b';  
// variable that stores the integer value of the character  
int asciivalue1 = ch1;  
int asciivalue2 = ch2;  
System.out.println("The ASCII value of " + ch1 + " is: " + asciivalue1);  
System.out.println("The ASCII value of " + ch2 + " is: " + asciivalue2);  
}  
}  

# Output: The ASCII value of a is: 97 || The ASCII value of b is: 98

#  approach2
public class PrintAsciiValueExample2  
{  
public static void main(String[] String)   
{  
int ch1 = 'a';  
int ch2 = 'b';  
System.out.println("The ASCII value of a is: "+ch1);  
System.out.println("The ASCII value of b is: "+ch2);  
}  
}  
# Output:The ASCII value of a is: 97 The ASCII value of b is: 98

# Using Type-Casting approach3
public class PrintAsciiValueExample3   
{  
public static void main(String[] args)   
{  
//characters whose ASCII value to be found  
char ch1 = 'a';  
char ch2 = 'b';  
//casting or converting a charter into int type  
int ascii1 = (int) ch1;  
int ascii2 = (int) ch2;  
System.out.println("The ASCII value of " + ch1 + " is: " + ascii1);  
System.out.println("The ASCII value of " + ch1 + " is: " + ascii2);  
}  
}  

# approach4 AsciiValueOfAllChracters.java
public class AsciiValueOfAllChracters  
{  
public static void main(String[] args)   
{  
for(int i = 0; i <= 255; i++)  
{  
System.out.println(" The ASCII value of " + (char)i + "  =  " + i);  
}  
}  
}   

# approach5 AsciiValueAtoZ.java
public class AsciiValueAtoZ  
{  
public static void main(String[] args)   
{  
for(int i = 65; i <= 90; i++)  
{  
System.out.println(" The ASCII value of " + (char)i + "  =  " + i);  
}  
}  
}  
