1. The bug is num1 and num2 are retrieved from input as strings. When I use the + operator with strings, JavaScript concatenates them instead of performing numeric addition.
2. To ensure that the function performs numeric addition, convert the inputs num1 and num2 to numbers before adding them. Modify line 11 to: <br>  let result = Number(num1) + Number(num2);

