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
* Variable name
* Its data type
* and example values you can assign them.

Next give TWO example variable names and TWO example variable assignments that are *WRONG* and explain why.
* Hint: your IDE can help you discover these!

## Answer to Part 2 - Interpretation
1. **Variables**: scriptTemplateLine1, scriptTemplateLine2, scriptTemplateLine3, scriptTemplateLine4, priceless
* Type: String (a sequence of characters)
* Example values: "Hello", "Full name"
2. **Variable**: people
* Type: int (integer)
* Example values: 3,18,500
3. **Variable**: ticketPrice
* Type: float (single-precision floating-point number)
* Example values: 0.02,12.0f,300.7
4. **Variable**: itemPrice
* Type: double (double-precision floating-point number)
* Example values: 3.5,18.234,87.54
5. **Variable**: trueOrFalse
* Type: boolean (true or false)
* Example values: true, false
 
- **Two example variable names and Two example variable assignments that are *WRONG*:**
* Example variable names: int numberOfCats, String yourName
* int numberOfCats = twenty (we cannot assign a word to an integer variable)
* String yourName = Lynn (we have to use " " when assigning a value to a string variable, the correct way to assign a value is: String yourName = "Lynn")
### Part 3 - Bonus: Play around with Java String Format Specifiers.

Pick several of the Java format specifiers below and define variables of the correct type utilize *sout* and *String.format* to view the resulting formats.

![Format Specifiers](JavaStringFormatSpecifiers.png)

### Part 4 - Submission
* Just as you did last week (Reference the Lab video in your Week 1 module), create a Spring2023 feature branch of your code
* Commit your working code to your local copy
* Push it to your Remote/origin branch (i.e. GitHub: Spring2023 -> origin/Spring2023)
* Then issue a Pull request to my instructor branch
    * Make sure to save the Pull request URL and submit it for the lab.


