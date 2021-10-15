# Part 2. A Little More of a Challenge...

1. Line 12 prints 3. The variable defined by keyword `var` can be accessed anywhere inside the function it is defined in. In this case, the variable `i` serves as a loop variable. After all iterations, `i` stops at 3. 
2. Line 13 prints 150. Similarly, the variable `discountedPrice` can be accessed anywhere inside the function. In the last iteration, `discountedPrice` is assigned the value $300 \cdot 1 / 2 = 150$. 
3. Line 14 prints 150. Similarly, the variable `finalPrice` can be accessed anywhere inside the function. In the last iteration, `discountedPrice` is assigned as 150, so the variable `finalPrice` is also assigned as 150. 
4. This function returns `[50, 100, 150]`, the array of discounted price. 
5. Line 12 returns nothing. There is even no function call. <!-- The variable defined by the keyword `let` can only be accessed within the block it is defined in. In this case, the variable `i` is defined as a loop variable, while `console.log()` is outside of the `for` loop.  -->
6. Line 13 returns an error. The variable `discountedPrice` can only be accessed within the `for` loop. 
7. Line 14 prints `150`. The variable `finalPrice` can be accessed within the whole function, while at the last iteration of the loop, `finalPrice` is assigned to 150. 
8. This function returns `[50, 100, 150]`, the array of discounted price. 
9. Line 11 returns an error. The variable defined by the keyword `let` can only be accessed within the block it is defined in. In this case, the variable `i` is defined as a loop variable, while `console.log()` is outside of the `for` loop.
10. Line 12 prints 3. The variable `length`, defined by the `const` keyword, can be accessed anywhere in the function and cannot be changed. The `length` of `prices` is 3. 
11. This function returns `[50, 100, 150]`, the array of discounted price. 

## Data Types
12. 
```
A. student.name
B. student['Grad Year']
C. student.greeting()
D. student['Favorite Teacher'].name
E. student.courseLoad[0]
```

## Basic Operators & Type Conversion 

13. 
```
A. '3' + 2 = '32' (2 is regarded as a string)
B. '3' - 2 = 1 ('3' is regarded as an integer)
C. 3 + null = 3 (null is 0)
D. '3' + null = '3null' (null is regarded as a string 'null')
E. true + 3 = 4 (true is 1)
F. false + null = 0 (false is 0, null is 0)
G. '3' + undefined = '3undefined' (undefined is regarded as a string)
H. '3' - undefined = NaN ('3' is regarded as the integer)
```

14. 
```
A. '2' > 1 True ('2' is regarded as 2 in integer and 2 > 1)
B. '2' < '12' False (Comparing 2 strings letter by letter is based on the dictionary order and '2' > '1' as we know)
C. 2 == '2'  True (2 and '2' have different types and then after convertion to numbers they are equal)
D. 2 === '2' False (2 and '2' have different types so they are not strictly equal)
E. true == 2 False (true is evaluated to be 1)
F. true === Boolean(2) True (true is evaluated to be 1 and Boolean(2) is evaluated to be 1 as well by the Boolean Conversion rules)
```

15. `a == b` means `a` and `b` have the same values without considering the types. If `a` and `b` have different types, they will be converted to numbers and then compared. `a === b` means `a` and `b` have the same values and same types. 

17. The result is `[2, 4, 6]`, which is the doubled input array. 

```javascript
let result = modifyArray([1, 2, 3], doSomething);
console.log(result.length);
for (let i = 0; i < result.length; i++) {
    console.log(result[i]);
}
```

## `setInterval()`, `setTimeout()`, `clearTimeout()`

19. The output is 
```
1
4
3
2
```