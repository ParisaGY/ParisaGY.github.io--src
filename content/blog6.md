Title: Learning python-part 2
Date: 2016-12-28 1:00
Category: Python


## Introduction to python iteration
1) For loop: The for statement is used to iterate over the elements of a sequence.
2) while loop: The while loop tells the computer to do something as long as the condition is met.

# Introduction to python-control-flow
The general Python syntax for a simple if statement is:
if condition:
    indentedStatementBlock

The general Python if-else syntax is

if condition:
    indentedStatementBlockForTrueCondition
else:
    indentedStatementBlockForFalseCondition


The syntax for an if-elif-else statement is indicated in general below:

if condition1:
    indentedStatementBlockForTrueCondition1
elif condition2:
    indentedStatementBlockForFirstTrueCondition2
elif condition3:
    indentedStatementBlockForFirstTrueCondition3
elif condition4:
    indentedStatementBlockForFirstTrueCondition4
else:
    indentedStatementBlockForEachConditionFalse


## Introduction to function
You can define functions to provide the required functionality. Here are simple rules to define a function in Python.

def functionname( parameters):
   "function_docstring"
   function_suite
   return [expression]
