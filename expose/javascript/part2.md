1. At line 12 it will print out value "3". Because "var" has no block scope. And after 3 iteration in for loop, i incremented to 3. 
2. At line 13 it will print out value "150". Because "var" has no block scope. And discountedPrice keeps the last updated value. Which is half value of 300.
3. At line 14 it will print out value "150". Because after the loop completes, finalPrice keeps the value from the last iteration of the loop.
4. The function will return [ 50, 100, 150 ] . The discountPrices function calculates and returns an array [50, 100, 150] by applying a 50% discount to each price in the input array [100, 200, 300].
5. ReferenceError: i is not defined. Becasue i is declared inside of for loop, outside i is out of the scope from i in the for loop, in order to avoid error, we need to re-declare i and initialize it, according to let rules.
6. ReferenceError: discountedPrice is not defined. The same as 5. discountedPrice variable is not declared and initialized outside of for loop.
7. At line 14 it will print out value "150". Different from 5 and 6, finalPrice is delcared by let keyword outside of the for loop, and in the for loop it can access and update the value of finalPrice, thus finalPrice keeps last updated value.
8. The function will return [ 50, 100, 150 ]. The same reason as 7. Variable discountedis delcared by let keyword outside of the for loop.
9. ReferenceError: i is not defined. This will cause a ReferenceError because i is not accessible outside the loop.
10. At line 12 it will print out value "3".  because length is a constant that's assigned the value of prices.length before the loop begins. So it remain unchanged.
11. **The function will return [ 50, 100, 150 ].The discounted array is declared with const, which means we cannot reassign discounted to point to a different array or a different value. However, const does not prevent us from modifying the contents of the array that discounted refers to. We can still perform actions such as pushing elements onto the array, changing existing elements, or otherwise manipulating the array's content.**
12. <br> A. student.name; <br> B. student['Grad Year']; <br> C. student.greeting(); <br> D. student['Favorite Teacher'].name; <br> E. student.courseload[0];
13. <br> A. '32' <br> In JS, the '+' operator is also string concatenation. So 2 is converted to '2' and concatenated with '3'. <br> B. 1 <br> The '-' operator is purely arithmetic and does not concatenate strings. JavaScript converts the string '3' to the number 3 and performs the subtraction with 2.  <br> C.  3 <br> 'null' is treated as 0 in numeric contexts. Therefore, adding 'null' to 3 results in 3.  <br> D. '3null' <br> When 'null' is combined with the '+' operator and one operand is a string, 'null' is converted to the string 'null' and concatenated.  <br> E. 4 <br> 'true' is treated as 1 in numeric contexts. So, 'true + 3' becomes '1 + 3', which equals 4. <br> F. 0 <br> Both 'false' and 'null' are treated as 0 in numeric contexts. Therefore, 'false + null' results in 0. <br> G. '3undefined' <br> Similar to 'null', when 'undefined' is used with the '+' operator and one operand is a string, 'undefined' is converted to the string 'undefined' and concatenated.  <br> H. NaN <br> The '-' operator tries to convert operands to numbers. 'undefined' becomes 'NaN' (special number) when converted to a number, **and any arithmetic operation with 'NaN' results in 'NaN'**.
14. <br> A. true <br> JavaScript performs type coercion, converting '2' to a number before comparing. Thus, 2 > 1 is true.  <br>  B.  false  <br>  dictionary comparison, first char "2" is greater than the first char "1"  <br>  C.  true <br> The == operator performs type coercion. It converts the string '2' to a number before comparing, resulting in 2 == 2.  <br> D.  false  <br>  The === operator checks for both value and type equality without performing type coercion. Since the types differ (number vs. string), the result is false. <br>  E.  false <br>   true is coerced to 1 when compared with numbers, so true == 2 is false because 1 is not equal to 2. <br>  F. true  <br> Boolean(2) returns true because any non-zero number is true in JavaScript. Both operands are of the same type (boolean) and value (true), so the strict equality (===) returns true  
15. A strict equality operator === checks the equality without type conversion, while an equality operator == converts different types of operands to numbers.<br> Use == if we need type coercion. <br> Use === if we require strick type and value equality.
16. [Link to part2-question16.js](./part2-question16.js)
17. modifyArray([1,2,3], doSomething) will return new array [ 2, 4, 6 ] <br> This array represents each of the original array elements doubled, which demonstrates a common use of callbacks for transforming data in JavaScript. modifyArray passed an array and function modifies each array by using for loop followed by rule of the function and return the modified new array.
18. [Link to part2-question18.js](./part2-question18.js)
19. 1 <br> 4 <br> 3 <br> 2















