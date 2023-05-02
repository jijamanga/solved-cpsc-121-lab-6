Download Link: https://assignmentchef.com/product/solved-cpsc-121-lab-6
<br>



Pointers and Structs

Your program will:

<ol>

 <li>Declare a Calculator object, and initialize it

  <ol>

   <li>0 for both values and + for last operator will be good</li>

   <li>You’ll have to initialize the pointer (with “new”) before initializing its value!</li>

  </ol></li>

 <li>Accepts a line of input that will be read like a calculator

  <ol>

   <li>Valid operations – The user is prompted, then, without choosing, just provides one of the below patterns

    <ol>

     <li>Full expressions: 3+5, when entered, displays/stores 8 (Used below)</li>

     <li>Partial expressions: +1, when entered, uses the previous results as a starting point. Continuing from the above example, displays/stores 9</li>

    </ol></li>

  </ol></li>

</ol>

<ul>

 <li>Repeat last operation: =, when entered, uses the previous operation’s results with the same operator and Right Hand value. If entered after the above statement, would display/store 10.</li>

</ul>

<ol>

 <li>You can make this run when no input is provided, just document it and let me know as the user!</li>

 <li>Quit: q, when entered, ends the execution of the program</li>

</ol>

<ol>

 <li>Apart from any whitespace that may be in the input string, any characters that are neither digits, an operator (+-*/%), or the quit command, should not be accepted; meaning the calculator command is rejected with a message given to the user. If the user’s input is rejected, no action should be taken.</li>

</ol>

<ol start="3">

 <li>Based on the user’s valid input, appropriately calculate, display, and store the answer in the LHValue member of your Calculator object

  <ol>

   <li>void processInput(Calculator * calc, string userInput)</li>

   <li>Function definition above must be used (argument types can’t be changed)</li>

  </ol></li>

 <li>Repeat step 2</li>

</ol>

Note: Don’t allow for division by 0!

If you’re unfamiliar with pointers, wait, look to the slides and/or try working on this assignment with the pointer temporarily converted to an ordinary variable.

Points:

<ul>

 <li>– Documentation, readability, format</li>

</ul>

1.5 – Proper use of Pointers

1.5 – Proper use of Structs

<ul>

 <li>– Proper program flow (conditionals, loops, etc)</li>

</ul>

2 – Filename and Header 2 – Output testing


