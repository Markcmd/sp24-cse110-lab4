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
