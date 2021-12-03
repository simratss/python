# Assignment 1

1. In the below elements which of them are values or an expression? eg:- values can be integer or string and expressions will be mathematical operators.
*

'hello'

-87.8

-

/

+

6
* is a mathematical operator, which is used for multiplication of two numerical variables.
e.g. x = 5, y=10, x*y = 50, or
in case of str and int variable, it will concatenate str variable.
x = 'abc', y = 5, x*y = 'abcabcabcabcabc'
'hello' is a str variable in python

-87.8 is float type variable
- is a mathematical operator, which is used for subtraction of two numerical variables.
x,y = 10,5
x-y = 5/ is a mathematical operator, which is used for division of two variables. it will return a float type variable.
e.g.
x,y = 10,5
x/y = 2.0+ is a mathematical operator, which is used for addition of two variables.
x,y = 10,5
x+y = 15
6 is a int type variable in python 

2. What is the difference between string and variable?

A string is a literal(i.e. type of values in python) which can be stored in a variable(or identifier)

while variable is a name given to entities like class, functions etc which can store values in memory. It helps to diffrentiate one entity from other
e.g
name = 'Simrat'
age = 28

A variable can hold a string but string cannot hold a variable

3. Describe three different data types.

* String
* Numeric(integer or float or complex)
* Boolean
* List
* Tuples
* Strings
* Dictionary

4. What is an expression made up of? What do all expressions do?

An expression is a combination of values, variables i.e. operands and operators.

5. This assignment statements, like spam = 10. What is the difference between an expression and a statement?


6. After running the following code, what does the variable bacon contain?

bacon = 22

bacon + 1

22 value is stored in bacon variable, because we haven't assigned any new value to the variable bacon

7. What should the values of the following two terms be?

'spam' + 'spamspam' = 'spamspamspam'

'spam' * 3 = 'spamspamspam'

8. Why is eggs a valid variable name while 100 is invalid?

This is because of Python's variable naming convention which is explained below.
In python, we have some naming conventions:
1. we cannot use any spaces in between the variable name.
    
    e.g. last name = 'syan', will give invalid syntax error, so we will use _.
         last_name = 'syan' is correct.

2. python is a case sensitive language.
    
    e.g name = 'simrat', print(Name) will give error, as name and Name are both diffrent variables.

3. reserved keywords like is, for, def, class, cannot be used as variable names.

4. variable name cannot start with a number.
    
    e.g. 100 variable name is invalied, but we can use var100, or v100 or v_100.
    
5. cannot use any other symbol expect _(underscore) in variable name.

9. What three functions can be used to get the integer, floating-point number, or string version of a value?

We can use the following in-built functions:

int() to get interger version of a value.

float() to get floating-point number version of a value

str() to get string version of a value

10. Why does this expression cause an error? How can you fix it?

'I have eaten' + 99 + 'burritos'

This expression cause an error because we cannot add a string value and numeric(int) value in python i.e. we cannot concatenate string and int by using + operator.
We can fix this error by converting 99 into string by using str() function.

'I have eaten' + str(99) + 'burritos'
