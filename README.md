Download Link: https://assignmentchef.com/product/solved-comp1400-lab4-programming-with-conditions
<br>
To evaluate a simple expression, you need to have two numbers and an operator. Assume that the normal operators of addition, subtraction, multiplication, and division should be recognized. So,

If operator is ‘+’ Æ number1 + number2 will be evaluated and displayed.

If operator is ‘-’  Æ number1 – number2  will be evaluated and displayed.

If operator is ‘*’  Æ number1 * number2  will be evaluated and displayed.

If operator is ‘/’  Æ number1 / number2  will be evaluated and displayed. Any other operators Æ Display “Unknown operator!” message.




Note: For division operations, divisor should not be zero.

<strong> </strong>

<strong>Part A: RAPTOR Exercise </strong>

<ol>

 <li>Watch the full video clip about <em><u>how to work with variable</u></em>.</li>

 <li>Watch the first half of the video clip about <em><u>how to make selections</u></em><u>.</u></li>

 <li>Start RAPTOR and create a flowchart that asks the user to enter two numbers (num1 and num2) and an operator (op) and displays the result of expression after evaluation.</li>

 <li>Your flowchart should check for division by zero.</li>

 <li>Save the flowchart to a file named “exprEval.rap” in the working directory on the PC you are using.</li>

 <li>Demonstrate the exprEval.rap file to GA/TAs and run with different input values.</li>

</ol>

<strong> </strong>

<strong>Part B: C Programming Exercise </strong>

<ol>

 <li>Write a program, represented by “exprEval.rap” flowchart, that allows the user to type in simple expressions of the form</li>

</ol>

number operator number




<ol>

 <li>The program evaluates the expression and displays the results at the terminal, to two decimal places of accuracy.</li>

 <li>The program, however, is allowed to call the scanf function only once.</li>

 <li>Remember to have the program check for division by zero.</li>

 <li>Save your program to a file named “exprEval.c” in the working directory on the PC you are using.</li>

 <li>Demonstrate the exprEval.c file to GA/TAs and run with different input values.</li>

</ol>




A sample interaction is shown below:







Enter a simple expression: <u>10 + 230</u>

Output: 10.00 + 230.00 = 240.00




Enter a simple expression: <u>13 * 2.5</u>

Output: 13.00 * 2.50 = 32.5




Enter a simple expression: <u>23.5 / 0</u> Output: Division by zero!




Enter a simple expression: <u>100 X 25.5</u> Output: Unknown operator!

<strong>Hint: </strong>Because Raptor has only two simple data types of number and string, the selection of an operator has to be done by comparing the operator input within double quotation marks, e.g., op == “+”. In C implementation, it is comparisons of two characters in the way as op == ‘+’, where op is a char type and the conversion specification for it is “%c”.

<strong> </strong>

<strong>EVALUATION: </strong>

You need to show your GA/TA the complete programs at the end of this lab, or at the beginning of your next lab. The marks you will receive for this lab are made of two parts: Lab work marks 10 and attendance marks 5. <strong>Total 15 marks</strong>.




<strong>Lab Work Mark</strong>: Your C code will be evaluated based on your solutions for the problems based on the following scheme:

<ol>

 <li>Does the code run and meet specifications?

  <ul>

   <li>Is input adequate and input data type properly validated? x Is processing adequate? x Is output correct and adequate?</li>

  </ul></li>

</ol>

x     Is the code compliable? Is the code run properly?

<ol start="2">

 <li>Is the code properly commented?

  <ul>

   <li>Is the program title, programmer’s first and last name, and the date posted at the top in a multi-line comment?</li>

  </ul></li>

</ol>

x     Is each significant step of the program properly commented? x       Are comments added to clarify details?

x    Are comments clear, accurate, neatly formatted, and have no misspellings?

<ol start="3">

 <li>Is the code properly formatted?

  <ul>

   <li>Are blocks of code indented according to their parent-child relationship? x Do curly braces line up vertically? x Is there an empty line between significant steps (blocks) of the program?</li>

  </ul></li>

</ol>

x     Is the width of the code contained within a reasonable limit so that minimal horizontal scrolling is required (with 800 x 600 monitor resolution), and there is minimal linewrapping when printed? x       Is camel-case notation used for variable, e.g. employeeLastName?

<strong>IMPORTANT: </strong>DO YOUR OWN CODE. ANY CODE SUSPECTED TO BE SIMILAR TO ANOTHER SUBMISSION WILL CAUSE BOTH SUBMISSIONS TO RECEIVE A ZERO MARK ON ALL LABS AND BE REPORTED FOR PLAGIARISM.


