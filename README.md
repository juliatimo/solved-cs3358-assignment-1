Download Link: https://assignmentchef.com/product/solved-cs3358-assignment-1
<br>
Write a C++ program to do the following :1. Create two 2D Arrays ( Array_l , Array_2 ). Each array is of size 3 x 3.2. Write a function to populate both arrays with distinct random numbers that are between 1 and 12.3. Write a function to display both arrays.4. Write a function to add Array_l to Array_2 and place the result in Array_3. Display Array_3.5. Write a function to multiply Array_l by Array_2 and place the result in Array_3. Display Array_3.6. Write a function to display the transposed of Array_l .7. Write a function to display the determinant of Array_l.8. Write a display the sum of elements of each row in Array_l.9. Write a display the sum of elements of each column in Array_l.10. Write a display the sum of both diagonal elements in Array_l.11. Use a function to determine whether Array_l is a special array. special Array is an arrangement of distinct numbers (i.e. each number is used once), usually integers, in a array grid, where the numbers in each row, and in each column, and the numbers in the main and secondary diagonals, all add up to the same number.12. Repeat steps 2 — 11 until the user terminates the program.

Note :1- Use the following formula to find the determinant of 3 by 3 Array :If Array : a b cA=[d e fg h i

ThenIAI = a(ei — fh) — b(di — fg) + c(dh — eg)2 – Use the following formula in order to find the special number Special Number = ( n ( 02+1) ) / 2

4 3 8 -■154 4 415se 15 15 15s■ 15

At the beginning of your program ( and before the #include statement ), include the following :Header comments (file documentation block) should be at the top of each file and should contain: Author / s, Due Date, Assignment Number, Course number and section, Instructor, and a brief description of the purpose of the code in the file. For example :// Author / s : (Your names here!!)1/ Due Date :1/ Programming Assignment Number 11/ Spring 2018 – CS 3358 – Section Number1/1/ Instructor: Husain Gholoom.1/1/ &lt;Brief description of the purpose of the program&gt;Variable names :• Must be meaningful.• The initial letter should be lowercase, following words should be capitalized, no other caps or punctuation ( i.e. weightInPounds ).• Each variable must be declared on a separate line with a descriptive comment.Named constants :• Use for most numeric literals.• All capitals with underscores ( i.e. TX_STATE_SALES_TAX )• Should occur at top of function, or global (only if necessary)Line length of source code should be no longer than 80 characters (no wrapping of lines).Indentation :• Use 2-4 spaces (but be consistent throughout your program).• Indent blocks, within blocks, etc.• Use blank lines to separate sections.

Comments for variables :All variable definitions should be commented as follows:int gender; // integer value for the gender,// 1 = Male , 2 = Female ,Rules :1. Your program must compile and run using latest version of codeblocks under windows.2. Your program must be documented according the style above . See the website for the sample programming style program.3. Must use random number generator to generate the 3-digit number .4. Must use at least 10 functions other than your main function.5. You are not allowed to use global Arrays , global variables … etc. You are also not allowed to classes and pointers.6. You must use the appropriate libraries in writing this program.7. Must properly format the output as it is shown on the sample run below. Replace my name with your name8. You must name your program as :o SP18_3358_S#_LastName_FirstName_PG1.cpp II S# is section NumberWhere LastName is your Last Name and FirstName is your First Name, and S# is your section number. For example , the file name should look something like :SP18-3358_0_Gholoom_Husain_PG1.cpp ( not .cbp ) or SP18-3358_1_Gholoom_Husain_PG1.cpp ( not .cbp ) or SP18-3358_2_Gholoom_Husain_PG1.cpp ( not .cbp )9. You must upload your programs no later than the starting of class time on the due date. No late assignments will be accepted. Everyone must upload their program electronically.Use Tracks To upload your program.

10. You must also turn in hard copy of your source code no later than the starting of class time on the due date . should the hard copy consist of more than one page , then , the hard copy must be stapled. if you are unable to turn in a printout during class, you can take the program to the computer science department and hand it to the front desk personal (Comal 211 ) before the deadline. Make sure that the front office stamps the program. Make sure that include the date and time. Finally ,make sure that they place the program in my mailbox. One hard copy per group.DO NOT slide your program under my office door — It will NOT be acceptedThe following points will be deducted if :• Incorrect file format such as uploading .cbp instead of .cpp , missing electronic copy , missing the hardcopy using .h and .cpp files , Compilation Errors , Using global variables, global arrays , vectors or global vectors … etc ( – 10 points )• Other ( 0.5 point each ) :• Logical Errors• Unable to read the source code due to unclear printing• Incorrect program file name.• Incorrect output format.• More than one hardcopy per group or Hard copy is not stapled.• Incorrect Style such as but not limited to Missing output header , output footer , comments or program documentations , missingroster number , missing section number, … etc

Sample RunWelcome to my Array program . The function of the program is to1. Create an 2 Arrays ( Array_1 , Array_2 ). Each Array is of size 3 x 3.2. Populate both Arrays with distinct random numbers that are between 1 and 12. Display both Arrays.3. Adding and multiplying Array_1 and Array_2.4. Displaying the transposed and the determinate of Array_1 .5. Displaying the sum of elements of each row of Array_1, displaying the sum of elements of each column of Array_1 , displaying the sum of both diagonal elements of Array_1.6. Finally , determining whether or not Array_1 is special array.7. Repeating the above steps until the user terminates the program. Array_18 1 63 5 74 9 2

Array_21 6 84 10 32 5 7

Sum of Array 1 and Array 2

9 7 147 15 106 14 9

Product of Array 1 and Array 224 88 10937 103 8844 124 73

Transpose of Array 18 3 41 5 96 7 2




Sum of numbers in first diagonal in Array 1 = 15Sum of numbers in second diagonal in Array 1 = 15The special number for Array 1 is 15The above is Special ArrayWould like to check another Array – Enter y or Y for yes or n I N for no y

Array_11 3 52 4 106 7 12Array_29 1 36 10 24 5 7Sum of Array 1 and Array 210 4 88 14 1210 12 19Product of Array 1 and Array 247 56 4482 92 84144 136 116Transpose of Array 11 2 63 4 75 10 12

Data Structures Programming Assignment 1Determinate of Array 1 = 36Sum of numbers in Row # 1 in Array 1 = 9Sum of numbers in Row # 2 in Array 1 = 16Sum of numbers in Row # 3 in Array 1 = 25Sum of numbers in Column # 1 in Array 1 = 9Sum of numbers in Column # 2 in Array 1 = 14Sum of numbers in Column # 3 in Array 1 = 27Sum of numbers in first diagonal in Array 1 = 15Sum of numbers in second diagonal in Array 1 = 17The special number is 15The above is not a special Array

Would like to check another Array – Enter y or Y for yes or n I N for no 5Error *** Invalid choice – Must enter y I Y I nINWould like to check another Array – Enter y or Y for yes or n I N for no hError *** Invalid choice – Must enter y I Y I n I NWould like to check another Array – Enter y or Y for yes or n I N for no nThis algorithm is implemented By Husain Gholoom


