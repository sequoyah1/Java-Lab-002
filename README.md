# Java-Lab-002

## Variables, Types and Operators

Be able to explain what variables are. Understand variable types, allowed names, and valid values.
Know how to create and use string, integer, floating-point, and boolean variables.

### Part 1 - PricelessScript.java - [MasterCard YouTube Ad](https://www.youtube.com/watch?v=Q_6stXKGuHo)

The lab template contains a program that prints the following:
```
2 tickets: $28.00
2 hotdogs, 2 popcorn, 2 sodas: $18.00
1 autographed baseball $45.00
real conversation with 11 year old son: priceless
true
```

Ignore the code that you don't fully recognize and concentrate on changing the variables to alter the MasterCard *Priceless* script to say:
```
3 tickets: $42.00
3 hotdogs, 3 popcorn, 3 sodas: $27.00
2 autographed baseball $90.00
watching the Giants win: priceless
false
```

### Part 2 - Interpretation
Take note of the various variables and their data types. Write a brief summary in this section of the README.md file listing the:
* Variable name: int people
* Its data type: integer
* and example values you can assign them.: changing int people from 3-4 changes the output to 4 hotdogs, 4 popcorn, 4 sodas: $36.00
*  Variable name: double itemPrice = 9.0
* Its data type: Floating point number
* and example values you can assign them.: This is the value of 1 hotdog 1 popped corn and 1 soda. Setting the value to 20.0 makes the total price output of line 2 $60.00


Next give TWO example variable names and TWO example variable assignments that are *WRONG* and explain why.
* Hint: your IDE can help you discover these!
* The only thing I can think of is itemPrice being used twice but having different assigned values. At the start item price is 9.0 and then for line 3 its changed to 45.0. 
* The example from the text was int a = 5; int b = 8; a and b are equal and then a = 3 makes a and b no longer equal. I dont know if this is wrong to do or not though. It works just fine, but I guess it could get messy to keep
track of in a longer program. 
* The IDE error check only returns redundant call to format.
### Part 3 - Bonus: Play around with Java String Format Specifiers.

Pick several of the Java format specifiers below and define variables of the correct type utilize *sout* and *String.format* to view the resulting formats.
String scriptTemplateLine5 = "Part 3: %s";
String part3 = "Part 3 test";
System.out.println(
String.format(scriptTemplateLine5, part3));
It outputs: Part 3: Part 3 test

[![Format Specifiers](JavaStringFormatSpecifiers.png)
### Part 4 - Submission
* Just as you did last week (Reference the Lab video in your Week 1 module), create a Spring2023 feature branch of your code
* Commit your working code to your local copy
* Push it to your Remote/origin branch (i.e. GitHub: Spring2023 -> origin/Spring2023)
* Then issue a Pull request to my instructor branch
    * Make sure to save the Pull request URL and submit it for the lab.
