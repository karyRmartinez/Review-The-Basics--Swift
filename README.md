# Review-The-Basics--Swift
Reviewing Swift Basic Fundamentals.
* Type Safety

* Variables / Constants

 Which of the following variables/constants are declared correctly? Select all that apply.

a. let nameOfPrincipal: Character = "Mrs. Watkins" // no

b. var temperatureOutside: Int = 90.7 // no

c. var isSummer: String = false // no

d. let whiteHouseAddress: Int + String = 1600 + "Pennsylvania Ave" //no

e. var peopleAtParty: Double = "95" //no



2. Boolean Evaluations 1
Which of the following expressions evaluate to true?

a. !(4 + 3 < 2 * 4)  // false

b. !(1 + 1 != 2) && !(3 >= 3) // false

c. (3 < 2 || (0 < 1 && 3 >= 3)) && true // ?

d. !!(!!true && !!false) // false

e. true && (true && (true && (true || false))) // true

3. Sum
You are given two variables a and b, compute their sum, store it in a variable named sum, then print the result.

Example 1
Input:
var a = 1
var b = 2

// var sum = a + b

Expected values:
sum = 3

Output: 
3


Example 2
Input:
var a = 13
var b = 22

Expected values: 
sum = 35

Output:
35

// var sum = a + b 
print(sum)


4. Seconds in Year
Determine the number of seconds in a year and store the number in a variable named secondsInAYear.

Hint:
The number of seconds in a year is 365 times the number of seconds in a day.
The number of seconds in a day is 24 times the number of seconds in a hour.
The number of seconds in a hour is 60 times the number of seconds in a minute, which is 60.
Solution
5. Number of Pixels
Your are given the width and height of a screen in pixels. Calculate the total number of pixels on the screen and store the result in a variable named numberOfPixels.

var width = 1920 
var height = 1080

Example 1
Input: 
var width = 4
var height = 3

Expected values:
numberOfPixels = 12

Example 2
Input:
var width = 1920
var height = 1080

Expected values:
numberOfPixels = 2073600

Hint:
Consider a 5x3 screen like this:
*****
*****
*****

The number of pixels on this screen is 5+5+5 = 5*3
Solution
6. Sum and Difference
You are given the sum and the difference of two numbers. Find out the values of the original numbers and store them in variables a and b.

var sum = 16 // a + b 
var diff = 4 // a - b

Example 1
Input: 
var sum = 16 
var dif = 4

Expected values:
a = 10
b = 6

Example 2
Input:
var sum = 2 
var dif = 0

Expected values:
a = 1
b = 1

Hint:
sum + diff = a + a + b - b
sum + diff = 2 * a
Solution
7. Swap Values
Given two variable a and b, swap their values. That is the new value of a will become the old value of b and vice versa.

var a = 1
var b = 2

Example 1
Input: 
a = 2
b = 1

Hint:
Just assigning a to the value of b and b to the value of a will not work.

var a = 1
var b = 2

a = b // a will have the value 2. The original value of a is lost
b = a // b will remain the same
Solution
8. Find last number
You are given a number a. Print the last digit of a.

var a = 123

Example 1
Input: 
var a = 123

Output:
3

Example 2
Input: 
var a = 337

Output:
7

Hint:
Use the remainder % operator.
Solution
9. Dog Years
You are given Rocky’s age in dog years. Print Rocky’s age in human years. You know that 1 human year is 7 dog years.

Example 1
Input: 
var rockysAgeInDogYears = 50

Output:
7
Solution
10. Alice's Age
x years from now Alice will be y times older than her brother Bob. Bob is 12 years old. How old is Alice?

var x = 3
var y = 2
var bob = 12

var alice = ?

Example 1
Input: 
var x = 3
var y = 2
var bob = 12

Expected values: 
alice = 27

Example 2
Input: 
var x = 1
var y = 3
var bob = 12

Expected values: 
alice = 38

Hint:
alice + x = y * (bob + x)
Solve for alice
Solution
11. Trading Oranges for Apples
You have x apples. Bob trades 3 oranges for 5 apples. He does not accept trades with cut fruit. How many oranges can you get from Bob and how many apples will you have left? The number of apples you will have left should be stored in a variable named apples. The number of oranges you will have after the trade should be stored in a variable named oranges.

var x = 17

Example 1
Input: 
var x = 17

Expected values: 
apples = 2
oranges = 9

Example 2
Input: 
var x = 25

Expected values: 
apples = 0
oranges = 15

Hint:
Use the division(/) and the remainder(%) operator
Solution
12. Boy and Girl Percentages
A class consists of numberOfBoys boys and numberOfGirls girls.

Print the percentage of boys in the class followed by the percentage of girls in the class. The percentage should be printed rounded down to the nearest integer. For example 33.333333333333 will be printed as 33.

var numberOfBoys = 20
var numberOfGirls = 60

Example 1
Input: 
var numberOfBoys = 20  
var numberOfGirls = 60

Output:
25 // percentage of boys
75 // percentage of girls
Solution
13. Boolean Evaluations 2
Which of the following expressions evaluate to true?

a. false || true
b. false && true
c. !false
d. !!!true
e. !(true && true)
Solution
14. Boolean Evaluations 3
Which of the following expressions evaluate to true?

a. 9 == 2
b. "Hello!" == "Hello!"
c. 19.0 >= 19.0
d. 9 > 7 && 7 < 10
Solution
15. Class Average
You are given three grades obtained by 3 students, which are stored in variables grade1, grade2, grade3 and all of type Double. Create a variable called yourGrade of type Double and give it a value. Print "above average" if your grade is greater than the class average or "below average" otherwise.

var grade1 = 7.0
var grade2 = 9.0
var grade3 = 5.0
Solution
16. Even or Odd
You are given a number. Print even if the number is even or odd otherwise.

let number = 2
