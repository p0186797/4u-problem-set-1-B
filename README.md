# 4u-problem-set-1-B

Create a java file called **ProblemSetOne.java** and upload it to this repo. For each program, do not have any extraneous print statements i.e. no prompts. The output must be exact.

---

Inside that file create a class called **MorseCodeQuestion**.

Write a program that reads one line from the user containing a sequence of characters and outputs if it represents morse code. Morse code will be a sequence made up of: "-", "." and " " (dashes, periods and spaces) except there cannot be 2 or more spaces in a row.

&nbsp;&nbsp; **Sample Input 1**

    -. --- -.-. -.

&nbsp;&nbsp; **Sample Output 1**

    yes


&nbsp;&nbsp; **Sample Input 2**

    -.  -...-.

&nbsp;&nbsp; **Sample Output 2**

    no

&nbsp;&nbsp; **Sample Input 2**

    -. a -.5.-.

&nbsp;&nbsp; **Sample Output 2**

    no
---

Inside that file create a class called **MaxQuestion**.

Write a program that reads pairs of lines from the user until the user enters QUIT. The first line in the pair will be there name. The second line will be there grade. Your program outputs the name(s) of the student(s) with the highest grade. 

**Input Specification**

There will always be 2n + 1 lines entered, the last one being QUIT. The first line in the pair will be their name. The second line will be an int between 0 and 100 inclusive.

**Output Specification**

The student(s) with the highest mark. If multiple students have the same highest mark, their names should be outputted in order of occurance with a comma and space separating them.

&nbsp;&nbsp; **Sample Input 1**

    Zack
    45
    Kelly
    60
    Slater
    55
    Jessie
    99
    QUIT

&nbsp;&nbsp; **Sample Output 1**

    Jessie
    
&nbsp;&nbsp; **Sample Input 2**

    Zack
    45
    Kelly
    60
    Screech
    99
    Slater
    55
    Jessie
    99
    Lisa
    99
    QUIT

&nbsp;&nbsp; **Sample Output 2**

    Screech, Jessie, Lisa

---

Inside that file create a class called **LatinSquareQuestion**.

Write a program that reads 4 lines from the user. Each line will consisted of 4 single digit numbers separated with a space (1 2 3 4) from 0 to 9 inclusive.

Your program outputs if the 4 lines make a Latin square.

1. Exactly 4 different single digit numbers are used from 0 to 9.

2. In each row, no numbers repeat.

2. The sum of each row is the same.

(There are more conditions but we will ignore them.)

For example:

1 2 3 4
4 3 2 1
2 4 1 3
3 1 4 2

Represents a Latin square because it uses exactly 4 single digits. No number repeats in each row. Each row sums to 10.

&nbsp;&nbsp; **Sample Input 1**

    1 2 3 4
    4 3 2 1
    2 4 1 3
    3 1 4 2

&nbsp;&nbsp; **Sample Output 1**

    yes

&nbsp;&nbsp; **Sample Input 2**

    2 3 4 5
    5 4 3 2
    1 6 3 4
    4 1 6 3

&nbsp;&nbsp; **Sample Output 2**

    no
