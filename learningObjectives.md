1. Define the boolean data type in Javascript.
   In computer programs, there are three types of data: text, numbers and Booleans. A Boolean data type is a value that can only be either true or false.

A true Boolean value might indicate that the object is valid (e.g. an email address has been typed correctly). A false Boolean value indicates that the object is invalid and has not been done correctly (e.g. you’ve forgotten to fill out a required field).

2. Define a conditional statement.
   Very often when you write code, you want to perform different actions for different decisions.

You can use conditional statements in your code to do this.

In JavaScript we have the following conditional statements:

    Use if to specify a block of code to be executed, if a specified condition is true
    Use else to specify a block of code to be executed, if the same condition is false
    Use else if to specify a new condition to test, if the first condition is false
    Use switch to specify many alternative blocks of code to be executed

3.  Define what iteration means in programming.
    In JavaScript an iterator is an object which defines a sequence and potentially a return value upon its termination.
    Once created, an iterator object can be iterated explicitly by repeatedly calling next(). Iterating over an iterator is said to consume the iterator, because it is generally only possible to do once. After a terminating value has been yielded additional calls to next() should continue to return {done: true}.

4.  Identify the comparison operators &&, || ! and explain when each operator should be used.
    To compare two values, you use a comparison operator. The following shows the comparison operators in JavaScript:
    Operator: < Meaning: Less than
    Operator: > Meaning: Greater than
    Operator: <= Meaning: Less than or equal to
    Operator: >= Meaning: Greater than or equal to
    Operator: == Meaning: Equal to
    Operator: != Meaning: Not equal to

    A comparison operator returns a Boolean value indicating that the comparison is true or not.

5.  Identify the logical operators &&, || ! and explain when each operator should be used.
    There are four logical operators in JavaScript: || (OR), && (AND), ! (NOT), ?? (Nullish Coalescing).

        || (OR)
        result = value1 || value2 || value3;
        The OR || operator does the following:

        Evaluates operands from left to right.
        For each operand, converts it to boolean. If the result is true, stops and returns the original value of that operand.
        If all operands have been evaluated (i.e. all were false), returns the last operand.

    <script>
    "use strict";

let firstName = "";
let lastName = "";
let nickName = "SuperCoder";

alert( firstName || lastName || nickName || "Anonymous"); // SuperCoder
</script>

&& (AND)
result = value1 && value2 && value3;

The AND && operator does the following:

    Evaluates operands from left to right.
    For each operand, converts it to a boolean. If the result is false, stops and returns the original value of that operand.
    If all operands have been evaluated (i.e. all were truthy), returns the last operand.

In other words, AND returns the first falsy value or the last value if none were found.

! (NOT)
result = !value;

The operator accepts a single argument and does the following:

    Converts the operand to boolean type: true/false.
    Returns the inverse value.

?? (Nullish Coalescing)
As it treats null and undefined similarly, we’ll use a special term here, in this article. For brevity, we’ll say that a value is “defined” when it’s neither null nor undefined.

The result of a ?? b is:

    if a is defined, then a,
    if a isn’t defined, then b.

In other words, ?? returns the first argument if it’s not null/undefined. Otherwise, the second one.

6.  Describe how a while loop statement works.
    The while loop loops through a block of code as long as a specified condition is true.

7.  Explain why we use conditional statements in programming.
    In JavaScript we have the following conditional statements:

        Use if to specify a block of code to be executed, if a specified condition is true
        Use else to specify a block of code to be executed, if the same condition is false
        Use else if to specify a new condition to test, if the first condition is false
        Use switch to specify many alternative blocks of code to be executed

8.  Explain why we need to use iteration to solve certain problems in programming.
    Iteration is the process of repeating steps. For example, a very simple algorithm for eating breakfast cereal might consist of these steps:

        put cereal in bowl
        add milk to cereal
        spoon cereal and milk into mouth
        repeat step 3 until all cereal and milk is eaten
        rinse bowl and spoon

The algorithm will repeat steps 3 and 4 until all the cereal and milk has been eaten.

9. Predict the behaviour of a short program that uses conditional statements and/or iteration
   ?

10. Evaluate basic expressions using comparison and logical operators.
    ?

11. Implement a solution to a problem that requires using conditional statements.
    ?

12. Implement a solution to a problem that requires using iteration.
    ?
