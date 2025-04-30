1. Line 12 will just print out 3 because since there are only three elements within the inputted prices list
2. Line 13 will just print out 150 because it is the last-update of the variable discountedPrice
3. Line 14 will just print out 150 because it is the last-update of the variable finalPrice
4. This function will return a list of 3 numbers, [50, 100, 150] because it just how the loop is set up, whenever we finished calculate one final price, it pushes that value to the list discounted, and it return discounted
5. Line 12 will cause an error because it is trying to access a variable (i) that is not defined in the scope
6. Line 13 will also cause an error because it is trying to access a variable (discountedPrice) that is not defined in the scope
7. Line 14 will just print out 150 because it is the last-update of the variable finalPrice
8. This function will return a list of 3 numbers, [50, 100, 150] because it just how the loop is set up, whenever we finished calculate one final price, it pushes that value to the list discounted, and it return discounted
9. Line 11 will cause an error because it is trying to access a variable (i) that is not defined in the scope
10. Line 12 will just print out 3 because since there are only three elements within the inputted prices list and we did attempt to modify the variable length at all
11. This function will return a list of 3 numbers, [50, 100, 150] because it just how the loop is set up, whenever we finished calculate one final price, it pushes that value to the list discounted, and it return discounted
12. 
    - A: student.name 
    - B: student['Grad Year'] 
    - C: student.greeting() 
    - D: student['Favorite Teacher'].name 
    - E: student.courseLoad[0]
13. Arithmetic
    - A: 32, because I think when using '+' and one of the operand is str object, JavaScript automatically change the other to a str object too
    - B: 1, because '-' changes both operands to numeric numbers
    - C: 3, because null = 0/nothing
    - D: 3null, because same as A, if using '+' and one of the operand is str object, JavaScript automatically change the other to a str object too
    - E: 4, because true = 1
    - F: 0, because both 0 and null = 0
    - G: 3undefined, because same as A, if using '+' and one of the operand is str object, JavaScript automatically change the other to a str object too
    - H: NaN, because '-' forces numeric operation, however, because undefined = NaN, the result is NaN
14. Comparison
    - A: true, because 2 is converted to number and is greater than 1 either way 
    - B: false, because 2 is greater than 1 when comparing as string objects
    - C: true, because the right-hand-side 2 is converted to numeric number and is the same as the left side
    - D: false, because they are different type
    - E: false, because true is converted to 1 which is smaller than 2
    - F: true, since they are all boolean values, and Boolean(2) is essentially just true since it's > 1
15. == operator allows type conversion before comparison, === operator checks the quality without type conversion
17. the result will be an array of 3 elements containing 2, 4, 6 because by the modifyArray function, each of the elements in the inputted array is double by the callback function (doSomething), and then getting pushed to the newArr
19. the output of the code would be 1 4 3 2 because 1 and 4 does not have setTimeout, and 3 is quicker than 2.