Task
Write a Person class with an instance variable, age, and a constructor that takes an integer, inititalAge, as a parameter.
The constructor must assign inititalAge to age after confirming the argument passed as inititalAge is not negative;
if a negative argument is passed as inititalAge, the constructor should set age to 0 and print Age is not valid, setting age to 0.
In addition, you must write the following instance methods:
1.yearPasses() should increase the age instance variable by 1.
2.amIOld() should perform the following conditional actions:
If age<13, print You are young..
If age>=13 and age<18, print You are a teenager..
Otherwise, print You are old..

Input Format
Input is handled for you by the stub code in the editor.
The first line contains an integer, T (the number of test cases), and the T subsequent lines each contain an integer denoting the age of a Person instance.

Constraints
1<=T<=4
-5<=age<=30

Output Format
Complete the method definitions provided in the editor so they meet the specifications outlined above; the code to test your work is already in the editor. 
If your methods are implemented correctly, each test case will print 2 or 3 lines (depending on whether or not a valid initialAge was passed to the constructor).
