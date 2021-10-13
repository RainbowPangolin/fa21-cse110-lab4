1. Line 12 will print `3` to the console. This is because the `var i` is accessible anywhere in the function, and was last incremented from 2 to 3 in the for loop.
2. Line 13 will print `150` to the console, because the last operation of the for loop assigned discountedPrice the value of `prices[2] * 0.5`.
3. Line 14 will print `150` to the console. The operation on discountedPrice to finalPrice doesn't change the value in this case, since there was no need for rounding. 
4. This function returns the array `[50, 100, 150]`. Essentially, the loop takes each `price` in `prices` and applies the discount `0.5` to them, and returns those `prices` as an array. Everything is half off, basically. 
5. Line 12 will return an error, as `i` is out of scope.
6. Line 13 will return an error, as `discountedPrice` is OOS.
7. Line 14 will print `150`. It is the same reasoning as from question 3, except we know that finalPrice was declared in the same scope as this console.log and so will not return an error like the previous two.
8. This function returns the array `[50, 100, 150]`. Exact same reasoning as question 4.
9. Line 11 would return an error, as `i` is out of scope.
10. Line 12 would return `3`, as it's within scope and `prices.length` is `3`.
11. The function returns the array `[50,100,150]` for the same reasoning as question 4. While `discounted` is a `const` array, we can push to `const` arrays so no errors will pop up.
12. Object:
    1.  student.name
    2.  student["Grad Year"]
    3.  student.greeting()
    4.  student["Favorite Teacher"].name
    5.  student.courseload[0]
13. Arithmetic
    1.  `32` - 3 is a string and 2 gets type casted to string due to precedence on the add operation
    2.  `1` - minus operation gives precedence to the number
    3.  `3` - null is treated as 0
    4.  `3null` - Add gives precedence to string
    5.  `4` - true is treated as 1
    6.  `0` - false and null are both treated as 0
    7.  `NaN` - undefined is NaN and NaN + number = NaN
    8.  `NaN` - Same as above.
14. Comparison
    1.  `true` - values become numbers when number is present
    2.  `false` - a dictionary comparison as strings, so 1 comes before 2
    3.  `true` - string becomes number\
    4.  `false` - strict equality checks the types- they're of different types
    5.  `false` - `true` becomes 1
    6.  `true` - `Boolean()` alwayas returns true for anything that's not 0, null, undefined, NaN, or empty string.
15. `==` checks equality and does type conversions, `===` checks equality without performing type conversions.


