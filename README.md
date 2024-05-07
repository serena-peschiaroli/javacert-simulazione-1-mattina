- 1. 


Which of these options when included at Line 1 will cause the given class to compile correctly?

public class FloatTest {

          public static void main(String[] args) {

                    // Line 1

                    int r =4;

                    float a=pi* r*r;

                    System.out.println(a);

          }

}

The are 2 correct answers

A. float pi = 3.14;
x B. float pi=3.14F;
C. Float pi=3.14f;
D. float pi:3.14F;
E. float pi:3.14;


___________________________________________________________________________________________________________

- 2. 

What is the output of the given code?
The are 1 correct answers


public class MethodTest {

public static String sayHello() {
return "Static Hello";

}

public String sayHello() {
return "Object Hello";

}

public static void main(String args[]) {
System.out.println(MethodTest.sayHello());
MethodTest test = new MethodTest();
String str = test.sayHello();
System.out.println(str);

}

}


A. Static Hello

Object Hello
B. Static Hello

Static Hello
C. Object Hello

Object Hello
D. Compilation Error
x E. Exception at runtime


- 3. 


public class StringSwitchTest {
public static void main(String[] args) {
String str = "two"+"";
switch (str) {
case "":
case "three":
case "five":
case "seven":
case "nine":
System.out.println("Odd number");
break;
case "two":
case "four":
case "six":
case "eight":
case "ten":
System. out.println("Even number");
break;
default:
System.out.println("Zero or above ten");

}

}

}


_____________________________________________________________________________________-

- 4. 


What is the result of the following program?

public class ExceptionTest2 {

          public static void main(String[] args) {

                    try {

                              String a = "0.0";

                              int num = Integer.parseInt(a);

                              System.out.println(num);

                    } catch (MyException exception) {

                     System.out.println("Invalid number format");

           }

      }

}

class MyException extends RuntimeException{

          public MyException(String message) {

                    super(message);

          }

}

The are 1 correct answers

A. Prints “0”
B. Prints “Invalid number format”
C. Prints “0.0”
x D. Unhandled exception at runtime
E. Compilation Error


_________________________________________________________________________________________________

- 5. 

Which are the static methods provided by the String class?

The are 3 correct answers

x A. valueOf()
B. contains()
C. spilt()
x D. format()
x E. join()
F. indexOf()

______________________________________________________________________________________________


- 6. 


How many times will the text “Finally block” be printed?


public class ForLoopTest {
public static void main(String[] args) {
for (int i = 0; i < 10; i++) {
try {
if (i == 3)
return;
} finally {
System.out.println("Finally block");

}

}

}

}


x A. 4
B. 5
C. 0
D. 1


____________________________________________________________________________________________

- 7. 


What all are true about method overloading?

The are 3 correct answers

A. The main method cannot be overloaded
x B. Static methods can be overloaded
C. Private methods cannot be overloaded
x D. Two methods with the same signature cannot be overloaded even if the return type is different
E. A subclass cannot overload a superclass method
x F. Constructors can be overloaded


_______________________________________________________________________________________________

- 8. 

What is the output of the following program?

The are 1 correct answers

public class ArrayListTestClass {

public static void main(String[] args) throws Exception {

ArrayList<String> list= new ArrayList<String>();

list.add("100");

list.add("200");

list.add("300");

list.add("400");

list.add("500");

int index = list.index0f(300);

System.out.println(index);

}

}


A. 3
B. 0
C. -1
D. -2
x E. Compilation Error
F. Runtime Error


______________________________________________________________________________________

- 9. 

Which import statements will help to compile the given program properly?

public class TestClass {

    public static void main(String[] args)

    {

        out.println(sqrt(10));      

    }

}

The are 2 correct answers

 A. import static java.lang.Math.*;   import static java.lang.System.out;
B. import static java.lang.Math;   import static java.lang.System;
x C. import static java.lang.Math.*;   import static java.lang.System.*;
D. import static java.lang.Math;   import static java.lang.System.out.*;
E. import static java.lang.Math.sqrt();   import static java.lang.System.out().*;


______________________________________________________________________

- 10. 

In the given code snippet, which line will cause the first compilation error?
The are 1 correct answers 

public static void main(String[] args) {

char ch;

int i;

ch++; // Line 1

i++; // Line 2

ch = i; // Line 3

i = ch; // Line 4

System.out.println(i + " "+ ch); // Line 5

}


A. Line 1
B. Line 2
x C. Line 3
D. Line 4
E. Line 5


______________________________________________________________________________________________


What is the output of the following program?

public class TestClass1 {

            static int c;

            public static void main(String[] args) {

                 int a = 10;

                 int b = 5;

                 if( b/(a*c)==0 ) {

                         System.out.println("Zero");

                 }

                 else { 

                         System.out.println("Non Zero");

                 }

            }

}

The are 1 correct answers

A. Prints Zero
B. Prints Non Zero
C. DivisionByZeroException at runtime
x D. ArithmeticException at runtime
E. Compilation Error because c is not initialized
F. Compilation Error because of division by zero


________________________________________________________________________________________________________


- 12. 

Which of these are true about String?

The are 3 correct answers

A. String is mutable
x B. One String can be appended to another string using the + operator
x C. equals() method can be used to compare two String objects
D. The length variable can be used to get the length of a String
x E. The toString() method can be used to convert an Integer to a String


______________________________________________________________________________________________


- 13. 

What is the output of the following program?

The are 1 correct answers


public class LabeledLoopTest {
public static void main(String args[]) {
int i, j;
outer: for (i = 1; i <= 5; i++) {
inner: for (j = 1; j <= 5; j++) {
System.out.print(j + " ");
if(j == 4) break outer;

}

}

}

}

A. Compilation error
B. Runtime error
C. Printing 1 2 3 4
D. Printing 1 2 3 4 5
E. Printing 1 2 3 4 for four times
F. Printing 1 2 3 4 5 for four times

______________________________________________________________________________________________

- 14. 

Which options are correct regarding operators?

The are 3 correct answers

x A. The assignment operator can be used to assign object references
x B. The unary operators require only one operand
C. The % operator divides one operand by another and returns the quotient as its result
x D. The instanceof operator is a relational operator
E. The logical AND operator always execute expressions on both sides


____________________________________________________________________________

- 15. 

What is the result of the following program?

public class ArrayTest {

    static int i;

    public static void main(String[] args) {

             int num = ++i;

             long[] arr = { 1, 1, 1, num, 1 };

             for (int i = 0; i < arr.length; i++) {

                         System.out.print(arr[i]);

             }

    }

}

The are 1 correct answers

A. Compilation error
B. Exception at runtime
x C. Prints 11111
D. Prints 11101
E. Prints nothing


____________________________________________________________________________________

- 16. 


How many lines will be printed by the loop in the program?

public class DoWhileTest {

            public static void main(String[] args) {                       

                        int i=0, sum=0;                       

                        do {

                                    i++;

                                    sum+=i;

                                    System.out.println(i);

                        }while(i<10 && sum<10);

            }

}

The are 1 correct answers

x A. 4
B. 5
C. 10
D. 11


_________________________________________________________________________________________

- 17. 

Which is the correct way to declare the variable bool without initialization in order to print false?

public class BooleanTest {

            // #Line1

            public static void main(String args[] ) {

                        // #Line2

                        System.out.print(bool);

            }

}

The are 1 correct answers

A. Declare bool in #Line1 as boolean
B. Declare bool in #Line2 as boolean
x C. Declare bool  in #Line1 as a static boolean
D. Declare bool  in #Line2 as a static boolean

_____________________________________________________________________________________________

- 18. 


Pick the right statements

The are 3 correct answers

A. Unchecked exceptions are to be handled for the program to compile
xB. A program will not compile if the checked exceptions are not handled
xC. ArithmeticException and NullpointerException are examples of unchecked exceptions
D. The catch block cannot be used to catch unchecked exceptions
xE. Throwable is the root class of exceptions and it belongs to java.lang package
F. The keyword ‘throws’ is used to throw an exception


__________________________________________________________________________________________________

- 19. 


Which one of the following is platform independent?

The are 1 correct answers

A. JRE
B. JDK
C. JVM
D. None of the above

- 20. 


Given the following classes/interfaces. Which of the following subtypes are legal

class C1{}

class C2{}

interface I1{}

interface I2{}

The are 3 correct answers

xA. class C3 extends C1 implements I1{}
B. class C4 extends C1, C2{}
xC. class C5 implements I1, I2{}
D. interface I3 implements I2{}
E. interface I4 extends C1{}
xF. interface I5 extends I2,I1{}


_____________________________________________________________________________________________


- 21. 


Which is the right way of the documentation comments in java?

The are 1 correct answers
A. /*

*

*/
x B. /**

*

*/
C. **/

*

*/
D. //

//





_____________________________________________________________________________________________-


- 22. 

What will be the output of the following program?

The are 1 correct answers


public class RoadTest {

final int driveSpeed = 50; // Line #1

void start() {

driveSpeed = 60; // Line #2

System.out.println("Started "+this.driveSpeed); // Line #3

}

public static void main(String args[]) {

RoadTest carTest = new RoadTest(); // Line #4

carTest.start();// Line #5

}

}


A. Prints “Started 60”
B. Compilation Error at Line #1
xC. Compilation Error at Line #2
D. Compilation Error at Line #3
E. Compilation Error at Line #4
F. Compilation Error at Line #5


__________________________________________________________________________


- 23. 


A statement written in the ternary operator can be rewritten using the following options?

The are 2 correct answers

A. Using for loop
B. Using simple if
C. Using if-else
D. Using Nested if
E. While loop
F. break and continue

__________________________________________________________________________


- 24. 


Which of the following statements is true about the given class?

class Student {

            private Student(String name, int studentId) {

            }

}

The are 1 correct answers

A. An object of Student class can be created only from a class belonging to the same package
B. An object of Student class can be created from any class
x C. An object of the Student class can be created only from the same class
D. An object of the Student class can be created only from its subclass

____________________________________________________________________________

- 25. 

What is the output of the following program?

public class ErrorTest {

            public static void main(String[] args) {

                        int a = 15, b = 18, c = 10;

                        if (a > b || a > c) {

                                    System.out.print(a);

                        } else if (b > c) {

                                    System.out.print(b);

                        } else {

                                    System.out.print(c);

                        }

            }

}

The are 1 correct answers

x A. 15
B. 18
C. 10
D. Compilation error
E. Runtime error


- 26. 


What is the output of the below program?

public class OperatorTest {

           public static void main(String[] args) {

                       int number = 50;

                       int newNumber = ++number;

                       int newNumber1 = --number;

                       System.out.println(newNumber + " " + number + " " + newNumber1--);

            }

}

The are 1 correct answers

A. 51 50 51
B. 51 50 49
x C. 51 50 50
D. 50 50 50

____________________________________________________________________________


- 27. 


In the below example which is the accessor method?

public class Employee {

            private int employeeId;

            public int getEmployeeId() {

                        return employeeId;

            }

            public void setEmployeeId(int employeeId) {

                        this.employeeId = employeeId;

            }

            public static void main(String[] args) {

                        Employee e = new Employee();

                        e.setEmployeeId(5);

                        e.printEmployeeId(e);

            }

            public void printEmployeeId(Employee employee) {

                        System.out.print(employee.getEmployeeId());

            }

}

The are 1 correct answers

x A. public int getEmployeeId()
B. public void setEmployeeId(int employeeId)
C. public static void main(String[] args)
D. public void printEmployeeId(Employee employee)

______________________________________________________________________

- 28. 

Which of the following is the correct class declaration as per naming conventions that contain the main method?

The are 1 correct answers

x A. public class CalculateResult
B. public class calculateResult
C. public class calculateresult
D. public class Calculateresult

_______________________________________________________________________

- 29. 

What will be the output of the following program?

public class MathClassTest {

            public static void main(String[] args) {

                        int val1 = -365;

                        int val2 = 365;

                        int abs1 = Math.abs(val1);

                        float abs2 = Math.abs(val2);

                        System.out.println("Total : " + (abs1 + abs2));

            }

}

The are 1 correct answers

A. Prints “Total : 730”
B. Prints “Total : 0”
C. Prints “Total : 365”
D. Prints “Total : -365”
x E. Prints “Total : 730.0”

________________________________________________________________________

- 30. 

What will be printed when the below code compiles and runs?

public class ArraySample {

            public static void main(String args[]) {

                        int arrSize = 5;

                        float[] arr = new float[arrSize];

                        float sum = 0;

                        for (int i = 0; i < arrSize; ++i)

                                    sum += arr[i];

                        System.out.println(sum);

            }

}
The are 1 correct answers

A. The code will not compile because there are no values assigned to the array
B. The code will throw a runtime exception because there are no values assigned to the array
x C. The code will print 0.0 when it runs;
D. The code will print 0 ten times when it runs;
E. The code will print 0.0 ten times when it runs;

___________________________________________________________________________-

- 31. 

Given the following classes and interfaces. Which of the given options compile without errors?

class C1{}

class C2{}

interface I1{}

interface I2{}

The are 2 correct answers

A. class C extends C1, C2{}
x B. class C4 extends C1 implements I1{}
C. class C5 implements I1 extends C1{}
x D. class C45 extends C1 implements I1,I2{}
E. class C6 extends C1,C2 implements I1,I2{}

_________________________________________________________________________

- 32. 

What is the output of the following program?

public class StringTest {

            public static void main(String[] args) {

                        String firstString = "World";

                        firstString.concat("Hello");

                        char firstChar = firstString.charAt(0);

                        System.out.print(firstChar);

                        char lastChar = firstString.charAt(firstString.length() - 1);

                        System.out.print(lastChar);

            }

}

The are 1 correct answers

A. Prints “Hd”
B. Prints “Wo”
C. Prints “Ho”
x D. Prints “Wd”
E. Does not compile
F. Throws exception


_________________________________________________________________________

- 33. 

Which of the following keywords are related to loops?

The are 3 correct answers

A. synchronized
x B. break
x C. continue
D. extends
x E. while
F. const

_____________________________________________________________________________

- 34. 

What will be the output of the following program?

The are 1 correct answers


public class SwitchTest {

public static void main(String[] args) {
int number = 2;
switch (number) {
case 2:
case 4:
case 6:
case 8:
case 10:
System.out.println("Even numbers up to 10 ");
break;
case 1:
case 3:
case 5:
case 7:
case 9:
case 12:
System.out.println("Odd numbers up to 10 ");
break;
default:
System.out.println("Zero");

}

}
}

x A. Prints Even numbers up to 10
B. Prints Odd numbers up to 10
C. Prints Zero
D. Compilation error
E. Runtime Error

_____________________________________________________________________________

- 35. 

Which of these applications are built using Java?

The are 3 correct answers

xA. Yahoo
xB. Amazon
xC. eBay
D. LinkedIn
E. Wikipedia
F. Pinterest

_____________________________________________________________________________


- 36.

Choose correct declarations of class variables?

The are 2 correct answers

A. class A {int var1;}
x B. class B {static int var1;}
x C. class C {public static int var1;}
D. class D {final int var1 = 0;}
E. class E {private int var1;}

_____________________________________________________________________________

What is the output of the following program?

The are 1 correct answers

public class ForLoopTest {

public static void main(String[] args) {
int i = 0;
for (; ; ) {
System.out.print(i + " ");
if (i >5) {
break;

}
i++;

}

}

}

x A. 0 1 2 3 4 5 6
B. Compilation Error
C. Runtime Error
D. 1 2 3 4 5 6
E. 0 1 2 3 4 


__________________________________________________________________________

- 38. 

The following code is saved in ‘C:/FirstProgram.java’. After compilation, which command will print the text “Java to Java ”?

public class FirstProgram {

              public static void main(String []args) {

                  System.out.println(args[1]+ " to  "+ args[1] );

               }

}

The are 1 correct answers

A. java FirstProgram.java Welcome to Java
B. java FirstProgram.java Welcome Java
C. java FirstProgram.class Welcome Java
x D. java FirstProgram Welcome Java
E. java FirstProgram Welcome to Java

______________________________________________________________________________

- 39. 

What is the result of the following program?

class A {

            private int val = 50;

            private void setVal(int val) {

                        this.val = val;

            }

            public int getVal() {

                        return this.val;

            }

}

public class TestClass {

            public static void main(String args[]) {

                        A obj = new A();

                        obj.setVal(100);

                        System.out.print(obj.getVal());

            }

}

The are 1 correct answers

x A. Compilation Error
B. Runtime Error
C. Prints 50
D. Prints 100

_________________________________________________________________________

- 40. 

What are the different ways to re-write below for loop?

 

for (int i = 0; i < 10; i++) {}

The are 3 correct answers
A. for (int i = 0; i < 10;) {
            i++;
            }
x B. int i = 0;
for (; i < 10; i++) {
}
C. int i = 0;
for (; i < 10) {
i++;
}
D. int i = 0;
for ( i < 10; i++) {
}
x E. int i = 0;
for (; ; i++) {
            if(i>=10)
                        break;
}


_____________________________________________________________________

- 41. 

What should be added at line X so that the below code compiles and prints “Bangladesh Bhutan India Nepal Sri Lanka”?

The are 1 correct answers

public class ArrayTest {

public static void main(String args[]) {
String[] array = {"India", "Sri Lanka", "Bangladesh", "Nepal",
"Bhutan"};
// Line X - insert code here
Arrays.sort(array);
for (String x : array) {
System.out.print(x + "");

}

}

}


A. Arrays.sort(array);
B. array.sort();
C. Collections.sort(array);
D. Comparable.sort(array);

______________________________________________________________________

- 42. 

What will be the result of the below following code?

The are 1 correct answers

public class ExceptionHandlingTest {

public static void main(String[] args) {
try {
int i = Integer.parseInt("xyz");
// Line 1
System.out.println(i);
} catch (Exception ex) {
// Line 2
System.out.println("Occurred Exception");
} catch (NumberFormatException ex) {
// Line 3
System. out. println("Occurred NumberFormatException");

}

}

}

A. Prints “XYZ”
B. Prints “Occurred Exception”
C. Compilation error within the try block
x D. Compilation error within a catch block
E. Prints “Occurred NumberFormatException”

___________________________________________________________________________

- 43. 


Which of the following are Java IDEs?

The are 3 correct answers

x A. Eclipse
B. MS Visual Studio
x C. NetBeans
D. Dreamweaver
x E. IntelliJ IDEA

____________________________________________________________________________

- 44. 

What will be the output when the below program runs?

 

The are 1 correct answers

public class InitializationTest {

static String name;

public static void main(String[] args) {

for (int i = 0; i < 10; i++) {

if (i % 3 == 0 && i != 0) {
continue;

}

if (i>8) {
break;

}

System.out.print(i + "");

}

}

}

A. 0 1 2 4 5 7 8
B. 1 2 3 4 5 7 8
C. 0 1 2 3 4 5 7
x D. 1 2 4 5 7
E. 0 1 2 3 4 5 6 7


_______________________________________________________________________

- 45. 


Which of the following line in the below program will show a compilation error?

The are 1 correct answers


System.out.println(name);

public class InitializationTest {

static String name;

public static void main(String[] args) {
String regNo;
Student student = new Student();
//Line 1
System.out.println(regNo); //Line 2
System.out.println(Student.rank); //Line 3
System.out.println(student.rank); //Line 4

}

}

class Student {

public static int rank;

}

A. Line 1
x B. Line 2
C. Line 3
D. Line 4

