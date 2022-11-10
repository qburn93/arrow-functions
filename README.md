You will create a function using the arrow syntax that should return the average marks of a subject. 
Your function should loop through the array that is passed in. 

For each student contained within, you should: 
1. Check if the subject passed into your function is in said student's results object; 
2. If it is, add it to a cumulative total of all results for that subject. 
3. Finally, return the average result for the subject.

You will only be asked to return the average marks for the subject english, but your function must be able to return the average marks if another subject name is used, and the tests will check for this.

1. Declare a variable named averagePoints using the keyword const

2. Assign it an arrow function, which should take two parameters named: arr and subject

3. The function should have a return statement

4. Declare a variable named: averageMarks using the keyword let

5. Assign it the return value from calling the function averagePoints, and passing it the students array and one of the following strings: 
'maths', 'english', 'cad', 'science', 'art'

6. log out the variable averageMarks to see its value

7. The function should return the correct value no matter which subject is used.