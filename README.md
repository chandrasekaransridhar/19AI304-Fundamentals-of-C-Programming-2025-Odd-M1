# 19AI304-Fundamentals-of-C-Programming-2025-Odd-M1
# IAPR-1- Module 1 - FoC
## 1. Implementation of basic C programs using Literals,Consonants, Variables, Data types.
## 2. Implementation of different categories of operators.
# Ex.No:1
  Build a C program to demonstrate the usage of different types of literals: integer, float, character, and string.  
# Date : 
# Aim:
To build a C program that prints integer, float,character, and string literals on the console using the printf() function.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside the main() function, use printf() to display each literal along with its size in bytes using sizeof() :
  
   3.1 Integer literal (e.g., 10) using `%d`
   
   3.2 Float literal (e.g., 3.14) using `%f`
   
   3.3 Character literal (e.g., 'A') using `%c`
   
   3.4 String literal (e.g., "Hello C") using `%s`
   
### Step 4: 
   Stop
# Program:
```c
#include <stdio.h>
int main(){
  int a=5;
  float flt=5.3;
  char cr='A';
  char string[]="SRIDHAR C";
  printf("int literal %d  and byte %lu\n",a,sizeof(a));
  printf("float literal %f and byte %lu\n",flt,sizeof(flt));
  printf("char literal %c and byte %lu\n",cr,sizeof(cr));
  printf("string literal %s and byte %lu\n",string,sizeof(string));
  return 0;
  
}
```
# Output:
<img width="773" height="266" alt="image" src="https://github.com/user-attachments/assets/4597e4de-04eb-4fca-a9de-734a1b990e09" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:2
  Build a C program to display the value of a macro constant and a constant variable.
# Date : 
# Aim:
  To build a C program that demonstrates the use of macro constants and constant variables.
# Algorithm:
### Step 1:
  Start  
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Define a macro constant `PI` with value `3.14159` using `#define`.
### Step 4: 
   Inside `main()`:
   
   4.1 Declare a constant integer variable `DAYS`
   
   4.2 Initialize it with the value `7`
   
### Step 5:  
  Use `printf()` to display the values of `PI` and `DAYS`.     
### Step 6:  
  Stop
# Program:
```c
#include <stdio.h>
#define PI 3.14159
int main(){
  const int days =7;
  printf("PI value: %f\n",PI);
  printf("Days: %d",days);
  return 0;
}
```
# Output:
<img width="776" height="208" alt="image" src="https://github.com/user-attachments/assets/827a19c2-fb2f-42b7-b2b3-23448487f256" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:3
  Build a C program to demonstrate the use of different data types such as int, float, double, and char, and display their values using printf().
# Date : 
# Aim:
  To build a C program that declares variables of various data types—integer, float, double, and character—initializes them, and prints their values on the screen.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside main(), declare and initialize variables of types int, float, double, and char.
### Step 4: 
   Display their values using printf().
### Step 5:    
   Stop
# Program:
```c
#include <stdio.h>
int main(){
  int a=5;
  char c='A';
  float m=3.14;
  double d=3.14159234;
  printf("The int value: %d\n",a);
  printf("The char value: %c\n",c);
  printf("The float value: %f\n",m);
  printf("The double value: %lf",d);
}
```
# Output:
<img width="771" height="264" alt="image" src="https://github.com/user-attachments/assets/c94050ee-e8ed-400d-945a-3dd8aaa48e07" />

# Result: 

# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:4
  Build a C program to perform arithmetic and bitwise operations on two integers entered by the user. The program should display: Arithmetic operations: addition, subtraction, multiplication, division, and remainder. Bitwise operations: AND, OR, XOR, left shift, right shift, and NOT.
# Date : 
# Aim:
  To build a C program that takes two integers as input and demonstrates the arithmetic and bitwise operations, displaying the results of each operation.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Declare two integer variables a and b.
### Step 4: 
   Prompt the user to enter two integers and read the input using scanf().
### Step 5:    
   Perform arithmetic operations on a and b:
   #### Sum (a + b)
   #### Difference (a - b)
   #### Product (a * b)
   #### Quotient (a / b)
   #### Remainder (a % b)
### Step 6: 
  Perform bitwise operations on a and b:
  #### AND (a &amp; b)
  #### OR (a | b)
  #### XOR (a ^ b)
  #### Left shift (a << b)
  #### Right shift (a >> b)
  #### Bitwise NOT of a (~a) and b (~b)
### Step 7:   
  Display the results of all operations using printf().
### Step 8:   
  Stop
# Program:
```c
#include <stdio.h>
int main(){
  int a,b;
  scanf("%d %d",&a,&b);
  printf("---------Arithmetic operations--------\n");
  printf("Addition operation: %d\n",a+b);
  printf("Subtraction operation: %d\n",a-b);
  printf("Multiply operation: %d\n",a*b);
  printf("Division operation: %d\n",a/b);
  printf("Modulo operation: %d\n",a%b);
  printf("\n");
  printf("-------Bit wise operations------------\n");
  printf("And operation: %d\n",a&b);
  printf("Or operation: %d\n",a|b);
  printf("Xor operation: %d\n",a^b);
  printf("Right shift operation: %d\n",a>>b);
  printf("Left shift operation: %d\n",a<<b);
  printf("Not operation a and b: %d %d\n",~a,~b);
  return 0;
}

```
# Output:
<img width="774" height="552" alt="image" src="https://github.com/user-attachments/assets/d4de3897-5b35-4d0e-9c8c-389aae9a0f3a" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:5
  Develop a C program to check whether a given character is a vowel, consonant, digit, or special symbol using the ternary operator.
# Date : 
# Aim:
  To develop and implement a C program that classifies a character as a vowel, consonant, digit, or special symbol using the ternary operator.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Input a character ch from the user.
### Step 4: 
   Check if ch is a digit ('0' to '9').
   
   If true → Print "Digit" → Go to Step 8.
   
   If false → Go to Step 5.
   
### Step 5:    
   Check if ch is an alphabet letter ('A' - 'Z' or 'a' – 'z').
   
   If true → Go to Step 6.
   
   If false → Go to Step 7.
   
### Step 6: 
   Check if ch is a vowel (a, e, i, o, u or A, E, I, O, U).
   
   If true → Print "Vowel" → Go to Step 8.
   
   If false → Print "Consonant" → Go to Step 8.
   
### Step 7:   
   Print "Special Symbol".
### Step 8:   
  Stop
# Program:
```c
#include <stdio.h>
int main(){
  char a;
  scanf("%c",&a);
  (a>='0' && a<='9')?printf("The entered the input is digit"):
  ((a>='a' && a<='z') || a>='A' && a<='Z')?
  (a=='A' || a=='E' || a=='I' || a=='O' || a=='U' || a=='a' || a=='e' || a=='i' || a=='o' || a=='u')
  ?printf("The entered input is vowel"):
  -printf("The entered input is consonant"):
  printf("The entered input is  special character");
  return 0;
}
```
# Output:
<img width="635" height="259" alt="image" src="https://github.com/user-attachments/assets/e00b2042-0fa2-416f-8aa9-439c655f27f9" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


