# Assignment-2

1) What are the two values of the Boolean data type? How do you write them?
The boolean value can be of two types only i.e. either True or False.Generally, it is used to represent the truth values of the expressions. For example, 1== 0 is True whereas 2<1 is False. 

2) What are the three different types of Boolean operators?
The three basic boolean operators are: AND, OR, and NOT.

3) Make a list of each Boolean operator's truth tables (i.e. every possible combination of Boolean values for the operator and what it evaluate ).

![image](https://user-images.githubusercontent.com/24777563/150099272-83509442-67f5-4fe0-acc0-7ab91fad7f77.png)

4) What are the values of the following expressions?
(5 > 4) and (3 == 5)
not (5 > 4)
(5 > 4) or (3 == 5)
not ((5 > 4) or (3 == 5))
(True and True) and (True == False)
(not False) or (not True)

Answer: (5 > 4) and (3 == 5) is False
not (5 > 4) is False
(5 > 4) or (3 == 5) is True
not ((5 > 4) or (3 == 5)) is False
(True and True) and (True == False) is False
(not False) or (not True) is True

5) What are the six comparison operators?
![image](https://user-images.githubusercontent.com/24777563/150099977-5c8c8cd9-31d2-422b-bec7-7035c7fa3376.png)

6) How do you tell the difference between the equal to and assignment operators?Describe a condition and when you would use one.

The “=” is an assignment operator is used to assign the value on the right to the variable on the left.
For example:a = 10;  b = 20; ch = 'y';
The ‘==’ operator checks whether the two given operands are equal or not. If so, it returns true. Otherwise it returns false.
For example: 5==5
This will return true.

7) Identify the three blocks in this code:
spam = 0
if spam == 10:
  print('eggs')
if spam > 5:
  print('bacon')
else:
  print('ham')
  print('spam')
  print('spam')
Answer: Nested if-else blocks

8) Write code that prints Hello if 1 is stored in spam, prints Howdy if 2 is stored in spam, and prints Greetings! if anything else is stored in spam.

![image](https://user-images.githubusercontent.com/24777563/150104757-ca44302f-60d4-4d58-aff4-6603e4285b57.png)

  
9) If your programme is stuck in an endless loop, what keys you’ll press?

An infinite loop occurs when a program keeps executing within one loop, never leaving it. To exit out of infinite loops on the command line, press CTRL + C.


10) How can you tell the difference between break and continue?

Break Statement:
The Break statement is used to exit from the loop constructs.
The break statement is usually used with the switch statement, and it can also use it within the while loop, do-while loop, or the for-loop.	The continue statement is not used with the switch statement, but it can be used within the while loop, do-while loop, or for-loop.
When a break statement is encountered then the control is exited from the loop construct immediately.
Syntax: break;
Continue Statement:
The continue statement is not used to exit from the loop constructs.
The continue statement is not used with the switch statement, but it can be used within the while loop, do-while loop, or for-loop.
When the continue statement is encountered then the control automatically passed from the beginning of the loop statement.
Syntax: continue;

11. In a for loop, what is the difference between range(10), range(0, 10), and range(0, 10, 1)?
There are three ways you can call range() : 
range(stop) takes one argument.
range(start, stop) takes two arguments.
range(start, stop, step) takes three arguments.
range(stop):
When user call range() with one argument, user will get a series of numbers that starts at 0 and includes every whole number up to, but not including, the number that user have provided as the stop. Example: range(10).
range(start, stop):
When user call range() with two arguments, user get to decide not only where the series of numbers stops but also where it starts, so user don’t have to start at 0 all the time. User can use range() to generate a series of numbers from X to Y using a range(X, Y). For Example range(0, 10).
range(start, stop, step):
When the user call range() with three arguments, the user can choose not only where the series of numbers will start and stop but also how big the difference will be between one number and the next. If the user doesn’t provide a step, then range() will automatically behave as if the step is 1. For Example range(0, 10, 1).

12. Write a short program that prints the numbers 1 to 10 using a for loop. Then write an equivalent program that prints the numbers 1 to 10 using a while loop.
Answer:

![image](https://user-images.githubusercontent.com/24777563/150104932-8b220bdc-e049-450f-8c8f-a29561cceed1.png)


14. If you had a function named bacon() inside a module named spam, how would you call it after importing spam?
This function can be called with spam.bacon().
