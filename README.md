# Lab 3: CrashMe

For this assignment, you and your partner will try and crash the included Java program in as many ways as possible. By editing lines of code and by using various inputs, you will document all of the different errors and exceptions you are able to cause at compile time and runtime. (This does not include syntax errors). Some errors you may try to cause are NullPointerExceptions, IndexOutOfBoundExceptions, StackOverflowErrors, etc. For some more inspiration here is a manual of errors and exceptions: https://drive.google.com/file/d/1skAJl91CHexfGpH3uN8893mp_DuXjLql/view?usp=sharing

## Pair Programming
To complete this assignment, we will use the pair programming model. One person will be the **Driver** and the other will be the **Navigator**. The Driver's responsibility is to write or edit the code/project. The Navigator's responsibility is to read the code as it is being typed, bring in outside resources, generate ideas, etc. Every 15-20 minutes, the two people will switch.  

At the end of the assignment, complete the following reflection about the pair programming model.
1. What was successful about the pair programming model for your group?
2. What changes would you make to this model to make it more successful for your group?
3. Why do you think software developers use this strategy when developing code?

1. Pair programming wasn't the most sucessful. Sometimes the navigator would want to take over, but I think if we worked at it, we could be a sucessful pair.
2. Switching whenever we need to switch, not every 15 minutes.
3. People who are coding for a long time can get tired of it, so it's good to take a break and get a different perspective. Another person looking at you code also helps you catch errors and get ideas.

## Documentation
Rather than submitting code for this assignment, you will edit and push this README.md file to document your progress.

For each exception and error you cause, report the following:
1. What exception or error did you cause?
2. How did you cause it?
3. What does that exception or error mean? Did it occur at compile time or runtime?

1. InputMismatchException
2. putting the wrong data type in the input
3. It means that it was asking for a number and we put a string. It occured at runtime.

1. OutOfMemoryError
2. We overloaded the memory with an ArrayList of integers
3. It means that there is no more room in the computer to run the code, runtime

1. StackOverflowError
2. We made an infinitely recursive function
3. The computer filled up the call stack with a whole lot of nothing, runtime

1. ExceptionInInitializerError
2. We created a variable that was 1 divided by 0 
3. Error was thrown because it couldn't make the variable with a math error, compile time

1. ArithmeticException
2. We did 1/0
3. This is not solvable, compile time

1. ArrayIndexOutOfBoundsExecption
2. We tried to grab an element of an array that didn't exist
3. This exception occurs at runtime. It means that the index of the array does not exist., run time

1. FileNotFoundException
2. We identified a file did not exist
3. it means the file we were identifiying didnt exist and this occured at runtime