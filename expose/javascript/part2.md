1.  Line 12 will print `3` because `prices` has the length of 3 and `var i` will run until the value is `3`.
2.  Line 13 will print `discountedPrice` which is the last value of the `discounted` array. This is the price before any rounding occurs.
3.  Line 14 will print the last `finalPrice` of the array `discounted` because the for-loop will terminate and the last value saved into `finalPrice` will be printed. This is the price after rounding. 
4.  The function will return `discounted` which is an array of numbers that reprsent the final discounted prices. The function takes in the parameters `prices` and `discount` where `prices` is an array of numbers and `discount` is the percentage to take off of the prices. The variable `discounted` will hold the `finalPrice` of the the product after the discount is applied which happens in the for-loop which iterates through `prices` and applies the `discount` to each of the numbers and adds it into `discounted`.
5.  The code will cause an error because the variable `i` is declared with the keyword `let` which restricts the scope of the variable to the for-loop block. Therefore, when the code tries to print `i`, it is outside the scope of the variable and will cause an error.
6.  The code will cause an error because the variable `discountedPrice` is declared and initialized with the `let` keyword which restricts the scope of the variable to the for-loop block. Trying to call the variable `discountedPrice` outside of the block will throw an error.
7. Line 14 will print the last `finalPrice` of the array `discounted` because the for-loop will terminate and the last value saved into `finalPrice` will be printed. This is the price after rounding. Since the variable is declared outside the for-loop and within the function, the scope is still valid. 
8. The function will return `discounted` which is an array of numbers that represent the final discounted prices. The function takes in the parameters `prices` and `discount` where `prices` is an array of numbers and `discount` is the percentage to take off of the prices. The variable `discounted` will hold the `finalPrice` of the the product after the discount is applied which happens in the for-loop which iterates through `prices` and applies the `discount` to each of the numbers and adds it into `discounted`. Since the variable is declared outside the for-loop and within the function, the scope is still valid. 
9. Line 11 will throw an error because the variable `i` is declared with the keyword `let` which restricts the scope of the variable to the for-loop block. Therefore, when the code tries to print `i`, it is outside the scope of the variable and will cause an error. 
10. Line 12 will print the value of `length` which is `3`
11. The function will return `discounted` which is an array of numbers that reprsent the final discounted prices. The function takes in the parameters `prices` and `discount` where `prices` is an array of numbers and `discount` is the percentage to take off of the prices. The variable `discounted` will hold the `discountedPrice` of the the product after the discount is applied which happens in the for-loop which iterates through `prices` and applies the `discount` to each of the numbers and adds it into `discounted`. Even though `discounted` is a `const` variable, the code is not changing the value of `discounted` and just adds values to the array so it will not throw an error.
12. Object Notation:
    1.  A: `student.name`
    2.  B: `student["Grad Year"]`
    3.  C: `student['greeting']()`
    4.  D: `student["Favorite Teacher"].name`
    5.  E: `student.courseLoad[0]`
13. Arithmetic
    1.  A: '32'
    2.  B: 1
    3.  C: 3
    4.  D: '3null'
    5.  E: 4
    6.  F: 0
    7.  G: '3undefined'
    8.  H: NaN
14. Comparison
    1.  A: true
    2.  B: false
    1.  C: true
    2.  D: false
    3.  E: false
    4.  F: true
15. `==` checks the equality of the two values being compared. This means that `true == 1` will equal `true` because the boolean value of 1 it true. `===` on the otherhand checks the equality without type conversion which means that if the values are different types, it will return `false`. So even though `==` equates true and 1 to be eqal, `===` will return false because they are different types. 
16. separate file
17. The function `modifyArray([1,2,3], doSomething);` will return an array of the original numbers of the array passed through as the parameter multilplied by 2. In the `modifyArray()` function, the array `[1,2,3]` is passed through and a for loop goes through each element of the array. Within the for loop, the parameter function that was passed through `doSomething()` is called on the `ith` value of the parameter array. `doSomething()` returns the num parameter passed through multiplied by 2 which is then pushed into the array `newArr` to store the values. This continues until the for loop exists, resulting in new array where the values of the old array are multiplied by 2. Then the new array is returned.
18. separate 
19. Output: 
    
    1

    4

    3
    
    2