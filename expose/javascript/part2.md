1. Line 12 will output a 3. This is because since i is declared as a var, it has function scope, and therefore can still be accessed outside of the for loop. It returns a 3 because the length of the prices array is 3, and the for loop runs 3 times until i is greater than the length of prices, so i will be 3 once the loop ends.
2. Line 13 will output 150. This is because discounted price is just the price while taking into account the discount. The final value that discountedPrice takes in the loop is 150 because 300 is the final value in prices, and 300 * (1-0.5) = 150, so 150 is output when discountedPrice is printed.
3. Line 14 will output 150. This is because finalPrice is the same as discountedPrice. The final value that discountedPrice takes in the loop is 150 because 300 is the final value in prices, and 300 * (1-0.5) = 150, so 150 is output when finalPrice is printed too since it takes the same value as discountedPrice basically. The reason finalPrice is basically the same as discountedPrice is because you are basically just multiplying 100 and then dividing by 100 because for the given prices array Math.round doesn't affect anything
4. This function will return an array of the discounted prices, so it returns [50,100,150]. For each price in prices, the discount is applied and then pushed to discounted array, so the discounted array will contain the same prices with the discount applied in the same order as in prices.
5. The code will error at line 12 because i is not defined since it has block scope (since is is defined by let) and therefore is only defined in the for loop, not in the whole function.
6. The code will error at line 13 because discountedPrice is not defined since it has block scope (since is is defined by let) and therefore is only defined in the for loop, not in the whole function.
7. The code will print 150 because finalPrice, although it is defined by let, it is not defined inside the for loop and has block scope in the entire function, so it is still defined when the print statement is run.
8. This function will return an array of the discounted prices, so it returns [50,100,150]. For each price in prices, the discount is applied and then pushed to discounted array, so the discounted array will contain the same prices with the discount applied in the same order as in prices. The let definition doesn't change anything because let means the variables that matter (prices and discounted) are still defined inside the function.
9. It says i is not defined because i is defined in block scope so it is only defined inside the for loop. This is because it is defined using const.
10. Line 12 prints 3 because length is defined outside the for loop, and takes the value of the length of the prices array.
11. This function will return an array of the discounted prices, so it returns [50,100,150]. This is because even though the discounted array is defined using const, you can edit the array itself, just can't reassign the entire variable.
12. 
    A.  student.name
    B.  student["Grad Year"]
    C.  student.greeting()
    D.  student["Favorite Teacher"].name
    E.  student.courseLoad[0]

13. 
    A. '32' (This is because 2 becomes a string and the strings concatenate to each other.)
    B.  1 (This is because '3' converts to an integer when being subtracted, and 3-2 = 1.)
    C.  0 (This is because null in addition converts to a 0, and 3 + 0 = 0)
    D.  '3null' (In this case, the + sign is string concatenation, so null converts to a string and concatenates to '3', so '3null' is output.)
    E.  4 (This is because true becomes an integer 1 in addition, so true + 3 = 3 + 1 = 4.)
    F.  0 (In this case, integer addition is used since false and null both don't use the + operator, so false becomes a 0 and null becomes a 0, so 0 + 0 = 0.)
    G.  '3undefined' (undefined becomes a string version of itself and concatenates to the string 3.)
    H.  NaN (This time, undefined must go through numeric conversion, so it becomes NaN and anything applied to NaN is NaN.)
14. 
    A. true (The string '2' becomes a number 2, and 2 > 1 is true.)
    B. false (The strings are compared in terms of their lexicographical order, and '2' is compared to '1', and since '2' is greater than '1', '2' < '12' returns false. The strings are compared character by character until different characters are compared.)
    C. true ('2' becomes a number because java converts all data types to numbers when comparing different types so it becomes 2 == 2 which is true.)
    D.  false (The strict equality operator compares without type conversion, so this is false.)
    E.  false (true converts to 1 since this is the regular equality operator, and 1 != 2.)
    F.  true (Boolean("2") evaluates to true, and true == true is true.)

15. === is the strict equality operator makes the check without type conversion, while == does type conversion before checking equality. Strict equality returns false automatically if two things are two different types.
16. Answer located in part2-question16.js.
17. [2,4,6] (This is returned because modifyArray takes in an array [1,2,3] and the doSomething function as parameters. All doSomething does is that it takes a number and returns 2 * that number. modifyArray loops through the array it takes in and applies the doSomething function to each of the numbers in the array before pushing the number into a newArr. Then, newArr is returned, and newArr contains the numbers in the same order as the original array but they are all multiplies by 2.)
18. Answer located in part2-question18.js.
19. The code outputs 1 4 3 2 (each number output on a different line).