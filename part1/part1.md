## Part1a

### var declaration

1.) values added: 20

2.) final result: 20

### let declaration

1.) values added: 20

2.) error, this because result is a declared with let so it would only be accessible through the if statement block

### const declaration

1.) error, it would never reach the point of printing since it will error on line 7 since it trying to reassign a const variable 

2.) error, it would never reach the point of printing since it will error on line 7 since it trying to reassign a const variable 

## Part1b

1.) it will print 3, since i is declared with var it will be accessible outside the for block so it will go from 1 to 3 after going up to the size of the prices length

2.) it will be 150, since discountedPrice is declared with var it will accessible anywhere in the function and depends on the value of current index of prices. it pass through the array [100, 200, 300] so the last one it would go through is 300 so it would be 300 * (1 - .5) which is 150

3.) it will print 150, since it was declared with var it is accessible anywhere in the function and it rounds the discounted price to the nearest cent. and final price changes depending on the value in the prices array it is looking at. The last value in the array is 300 and the discounted price is 150 so the final price 150 rounded to the nearest cent which is 150

4.) it will return the array of [50, 100, 150]. This is because it is returning discounted which is declared as a empty array. then we push is all the values of the prices parameter * (1 - discount)

5.) error, since i is declared with let would not be accessible outside the for loop

6.) error, since discountedPrice is declared with let would not be accessible outside the for loop

7.) 150, even though is declared with let the log statement is within the function code block that it was declared in. So it is still accessible and has the same value as if it were a var

8.) it will return the array of [50, 100, 150]. This is because it is returning discounted which is declared as a empty array. then we push is all the values of the prices parameter * (1 - discount)

9.) error, since i is declared with let would not be accessible outside the for loop

10.) 3, since length is initialized as prices.length which has 3 items in it, and even though it is declared with const it is accessed in the same code block for the function

11.) it will return the array of [50, 100, 150]. This is because it is returning discounted which is declared as a empty array. then we push is all the values of the prices parameter * (1 - discount)

### Data Types

12.) 

a.) student.name

b.) student['Grad Year']

c.) student.greeting()

d.) student['Favorite Teacher'].name

e.) student.courseLoad[0]

### Basic OPerators & Type Conversion

13.) 

a.) '32' the 2 is converted to a string a concatenated with '3'

b.) 1 the 3 is converted to a number and subtracted by 2 

c.) 3 null is converted into a number of 0 and added to 3

d.) '3null' null is converted to the string 'null' and concatenated with '3'

e.) 4 true is converted to a 1 added to to 4

f.) 0 false and null are both converted to the number 0 and added together 

g.) 3undefined as the undefined is converted to a string of 'undefined' add concatenated with '3'

h.) NaN undefined cannot be converted to a number so the whole expression become not a number

14.)

a.) true, 2 is converted to a number and is greater than 1

b.) false, it used alphabetical order and 1 comes before 2

c.) true, '2' is converted to a number so it is equal to 2

d.) false, '2' is not the same type of the number 2

e.) false, true is equal to 1 as a number 

f.) true when specifically casted to a boolean it coverts anything that is not 0, null, undefined, NaN, and "" as false and everything else as true so 2 becomes 2

15.) == converts the two things it comparing to the same type, while === adds another conditional that they must already by of the same type

### Loops

16.) [part1b-question16.js](./part1b-question16.js)

### Functions

17.) is creates an array of [2,4,6]. since the modifyArray creates and empty array. Then in a for loop it passes the element in the parameter array into the callback function, the callback function simply multiplies it by 2 and returns. then the value is pushed into the new array.

### setInterval(), setTimeout(), clearTimeout()

18.) [part1b-question18.js](./part1b-question18.js)

19.) 1 4 3 2 