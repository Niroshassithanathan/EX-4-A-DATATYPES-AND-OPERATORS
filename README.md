# EX-4-A-DATATYPES-AND-OPERATORS
## AIM:
  write a Program to check whether a given Value=Y is upper case, lower case, number or special character using conditional operator ?
## ALGORITHAM :
1.Start

2.Declare a variable Y to store the character input.

3.Prompt the user to enter a character and read it into the variable Y.

4.Use the conditional operator (?) to check the type of character:

5.End.
## PROGRAM :
```
#include <stdio.h>
int main()
{
char a='A';
((a>='a')&&(a<'z'))?printf("Lower"):((a>='A')&&(a<'Z'))?printf("Upper"):((a>1)&&(a<=40))
?printf("Symbol"):printf("Number");
}
```
## OUTPUT :
![image](https://github.com/Niroshassithanathan/EX-4-A-DATATYPES-AND-OPERATORS/assets/121418437/717f65ff-4768-4cdc-9ca6-ffda8f49dc3a)

## RESULT :
Thus , The C program has been executed successfully.
