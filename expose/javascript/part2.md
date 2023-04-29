1. It prints `3`. This is because there are 3 elements in the input array, so the for-loop will increment `i` up by one 3 times. Then the print statement comes after the loop ends. Since `i` has function scope, the print statement takes the value that it was last defined since the print statement is in the fucntion.
2. It prints `150`. This is because the variable it's printing gets reassigned for the final time using the last element in the list which is `300`. The variable has function scope so it can be accessed by the print statement.
3. It prints `150`. This is because the variable it's printing gets reassigned for the final time using the last element in the list which is `300`. The variable has function scope so it can be accessed by the print statement.
4. It returns a list: `[ 50, 100, 150 ]`. This is because after every iteration of the for-loop, `finalPrice`, which is calculated using the input values, gets pushed to `discounted`. `discounted` is in the same function block as the return statement and everything in the for-loop so it can be accessed by the return statement and the for-loop.
5. It returns an error "ReferenceError: i is not defined". This is because the print statement is trying to access `i` which can only be accessed within the for-loop, while the print statement is outside of the for-loop.
6. It returns an error "ReferenceError: discountedPrice is not defined". This is because the print statement is trying to access `i` which can only be accessed within the for-loop, while the print statement is outside of the for-loop.
7. It prints `150`. This is because the variable it's printing gets reassigned for the final time using the last element in the list which is `300`. The variable has block scope (which is just the function) so it can be accessed by the print statement and everything inside of the function.
8. It returns a list: `[ 50, 100, 150 ]`. This is because after every iteration of the for-loop, `finalPrice`, which is calculated using the input values, gets pushed to `discounted`. `discounted` is in the same function block as the return statement and everything in the for-loop so it can be accessed by the return statement and the for-loop.
9. It returns an error "ReferenceError: i is not defined". This is because the print statement is trying to access `i` which can only be accessed within the for-loop, while the print statement is outside of the for-loop.
10. It prints `3` since `length` was assigned the length of the list `prices`. There are 3 elements in that list.
11. It returns a list: `[ 50, 100, 150 ]`. This is because after every iteration of the for-loop, `discountedPrice`, which is calculated using the input values, gets pushed to `discounted`. `discounted` is in the same function block as the return statement and everything in the for-loop so it can be accessed by the return statement and the for-loop.
12A. `student.name`

12B. `student['Grad Year']`

12C. `student.greeting()`

12D. `student['Favorite Teacher'].name`

12E. `student.courseLoad[0]`

13A. `"32"`. The number is converted into a string and the strings get concatenated together.

13B. `1`. The string is converted into a number and the subtraction operator is performed on the numbers.

13C. `3`. `null` is converted to 0 and the numbers are added together.

13D. `3null`. `null` is converted to the string `"null"` and the two strings are concatenated together.

13E. `4`. `true` is converted to `1` and the numbers are added together.

13F. `0`. `false` and `null` are converted to 0 and the numbers are added together. 

13G. `3undefined`. `undefined` is converted to the string `"undefined"` and the two strings are concatenated together.

13H. `NaN`. The two operands get converted into numbers, so `"3"` becomes `3` and `undefined` becomes `NaN`. The subtraction operator applied to `NaN` results in `NaN`.

14A. `true`. `'2'` is converted to the number `2`, which is greater than 1.

14B. `false`. The string `'2'` is lexographically smaller than `'12'`.

14C. `true`. `==` automatically converts the string `'2'` to a number, so they become the same number.

14D. `false`. `===` does not do type conversion. The number 2 is different from the string '2'.

14E. `false`. `true` is converted to `1`. `1` is not equal to `2`. 

14F. `true`. `Boolean(2)` is `true` since it will convert all non-zero numbers to `true`, and `true` is equal to `true`.

15. `==` compares values after performing type conversion if necessary so it's a loose comparision. `===` does a strict comparision so it compares both value and type of the operands without any type conversion.

17. `[ 2, 4, 6 ]`. In `modifyArray`, for each iteration of the loop, each number of the input array first gets passed through the callback function `doSomething`, which multiplies the number by 2. Then the result of get pushed to the return array. This is why the result is the input array but with the elements each multipled by 2.

19.
```
1
4
3
2
```