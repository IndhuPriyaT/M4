# EX-16-LEFT-SHIFT-OPERATION
## AIM
To write a C Program to perform the basic left shift operation for 44 integer number with 3 shifts.

## ALGORITHM
1.	Start the program.
2.	Assign values of a and b as 44 and 3.
3.	Use left shift operator (<<) and shift the value of a three times.
4.	Display the result.
5.	Stop the program.

## PROGRAM
```
#include <stdio.h>
int main()
{
 int x=44,b=3;
 x<<=b;
 printf("After Left shift Operation: %d",x);
return 0;
}
```

## OUTPUT

![Screenshot 2025-05-10 152812](https://github.com/user-attachments/assets/ed8339aa-051d-4645-b034-2facb07abef3)










## RESULT
Thus the program to perform the basic left shift operation for 44 integer number with 3 shifts has been executed successfully.




 
 


# EX-17-TWO-NUMBERS-ARE-EQUAL-OR-NOT


## AIM

Write a C Program to check whether the two numbers are equal or not using simple if statement.

## ALGORITHM

1.	Start the program.
2.	Read two numbers.
3.	If first number is equal to second number, display both are equal.
4.	Otherwise display both are not equal.
5.	Stop the program.

## PROGRAM
```
#include <stdio.h>
int main()
{
 int a,b;
 scanf("%d%d",&a,&b);
 if(a==b)
  printf("Both the numbers are equal.");
else
 printf("Both the numbers are not equal.");
}
```

## OUTPUT
![Screenshot 2025-05-10 152942](https://github.com/user-attachments/assets/e69bca1b-df36-4d7c-8d1a-60c4011701b0)

           
## RESULT

Thus the program to check whether the two numbers are equal or not using simple if statement has been executed successfully
 
 


# EX-18-STRING-LOWERCASE-CONVERSION
## AIM
Write a C Program to convert the given string into lowercase.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using tolower( ) function convert the given string into its lowercase.
4.	Display the result.
5.	Stop the program.

## PROGRAM
```
#include <stdio.h>
#include <string.h>
#include <ctype.h>
int main()
{
 char s[10];
 scanf("%[^\n]",s);
 for(i=0;s[i];i++)
  s[i]=tolower(s[i]);
 printf("%s",s);
 }
```

## OUTPUT
![Screenshot 2025-05-10 153652](https://github.com/user-attachments/assets/2a031a48-a6a8-4b73-9df2-bdbf51f5beb3)





## RESULT
Thus the program to convert the given string into lowercase has been executed successfully
 
 


# EX-19-COUNT-OF-WORDS-IN-A-STRING
## AIM
Write a C Program to count the total number of words in a given string using do While loop.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using for loop, inspect the string character by character.
4.	Whenever a space is encountered increment count by 1.
5.	Display the result.
6.	Stop the program.

## PROGRAM
```
#include <stdio.h>
int main()
{
 char s[200];
 scanf(" %[^\n]",s);
 int i=0,w=1;
 do{
     if(s[i]==' ')
        w++;
     i++;
    }while(s[i]!='\0');

printf("Total no.of words are:%d",w);
}

```

## OUTPUT
![Screenshot 2025-05-10 154017](https://github.com/user-attachments/assets/74e0f380-a677-4006-8ace-1b4fe36ec765)





## RESULT
Thus the program to count the total number of words in a given string using do While loop has been executed successfully
 
 


# EX  -20 -COMPARING TWO STRINGS
## AIM
write a Program to compare two strings without using strcmp().
## ALGORITHM
Step 1: Start the program.
Step 2: Declare two character arrays c1 and c2 of size 100 to store the strings. Also, declare an integer variable
             flag and initialize it to 0, and i for indexing.      
Step 3: Read the first string c1 using scanf("%[^\n]", c1); — this reads input until a newline is encountered 
            (i.e., can include spaces).
Step 4: Read the second string c2 using scanf("%s", c2); — this reads input until a space or newline (i.e., no 
            spaces in the second string).
Step 5: Start comparing characters of both strings from index i = 0.
Step 6: Repeat the following while neither c1[i] nor c2[i] is '\0' (i.e., end of string):
•	If c1[i] is not equal to c2[i], set flag = 1.
•	Increment i by 1.
Step 7: After the loop, check the value of flag:
•	If flag == 0, print "strings are same".
•	Otherwise, print "strings are not same".
Step 8: End the program.

## PROGRAM
```
#include <stdio.h>
#include <string.h>
int main()
{
 char c1[100],c2[100];
 scanf(" %[^\n]",c1);
 scanf(" %[^\n]",c2);
 int flag=0,i;
 while(c1[i]!='\0' && c2[i]!='\0')
{
  i++;
  if(c1[i]!=c2[i])
  flag=1;
}
 if(flag==0)
 printf("strings are same.');
 else
 printf("strings are different.");
}
```


## OUTPUT
![Screenshot 2025-05-10 155448](https://github.com/user-attachments/assets/f59fb27d-7a1b-4492-b114-337bd31b9a2b)

 

## RESULT
Thus the C Program to compare two strings without using strcmp() has been executed successfully.

