# Trainee-Problem-Statement
Submitted by : Nishika Batra

Problem Statement 1: Write a script in python or javascript to find the solution of the following problem
How many two or more digit numbers can you make such that digits on left are always smaller than the digits on the right in the number?
           
For e.g. 189 is valid (because 1<8<9 and it is at least two digit number)

198 is not valid

288 is not valid


Problem Statement 2: Write a script in python or javascript that would take two numbers and generate the additional steps in a json format.

For e.g. num1=1489, num2=714

Then output should be

{

"step1": { "carryString": "1", "sumString": "3" },

"step2": { "carryString": "11", "sumString": "03" },

"step3": { "carryString": "111", "sumString": "203" },

"step4": { "carryString": "111", "sumString": "2203" }

}
