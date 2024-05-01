1. What will happen at line 12 and why? If the code causes an error, explain why. 
   - 3

2. What will happen at line 13 and why? If the code causes an error, explain why. 
    - 150. 

3. What will happen at line 14 and why? If the code causes an error, explain why.
   - 150. because the finalPrice = Math.round(discountedPrice * 100) / 100 = 150, and finalPrice is not a let/const type so it can be accessed by the console.log.

4. What will this function return? Give a brief explanation why. If the code causes an error, explain why.
   - [ 50, 100, 150 ]. The return statement in line 16 will return the array of discounted which contains the prices after discount.

5. What will happen at line 12 and why?  If the code causes an error, explain why.
    - ReferenceError: i is not defined. i is a variable defined as let type which is only valid with the block it is defined, so when calling it outside of its block, the varible will be undefined and cause error.
  
6. What will happen at line 13 and why? If the code causes an error, explain why. 
   - ReferenceError: discountedPrice is not defined. the variable discountedPrice is defined as a let type within the for loop, so calling it outside of the for loop will cause error because let type is only valid within the block it is defined. 

7. What will happen at line 14 and why? If the code causes an error, explain why. 
   - 150. since finalPrice is not declared as a let/const type so it can be called outside of the block it was declared, and the last stored value of finalPrice is 150, so the value. 

8. What will this function return? Give a brief explanation. If the code causes an error, explain why. 
   - [ 50, 100, 150 ]. The function will return the value of discounted. Although discounted is defined as a let type but calling it from the same scope is valid.

9. What will happen at line 11 and why? If the code causes an error, explain why.
    - ReferenceError: i is not defined. i is defined as a let type which can't be called outside of the scope it is defined. 

10. What will happen at line 12 and why? If the code causes an error, explain why.
    - 3. Calling const length within the scope it is defined is valid.

11. What will this function return? Give a brief explanation. If the code causes an error, explain why. 
    - [ 50, 100, 150 ]. discountedPrice will calculate the price after 50% discount and store it to discounted by push. 

12. Given the above Object, write the notation for:
    A. Accessing the value of the name property in the student object
        - student.name
    B. Accessing the value of the Grad Year property in the student object
        - student['Grad Year']
    C. Calling the function for the greeting property in the student object
        - student.greeting()
    D. Accessing the name property of the object in the Favorite Teacher property in student
        - student['Favorite Teacher'].name
    E. Access index zero in the array of the courseLoad property of the student object
        - student.courseLoad[0]

13. Arithmetic
    A. '3' + 2
        - '32'
    B. '3' - 2
        - 1
    C. 3 + null
        - 3
    D. '3' + null
        - '3null'
    E. true + 3
        - 4
    F. false + null
        - 0
    G. '3' + undefined
        - '3undefined'
    H. '3' - undefined
        - NaN

14. Comparison
    A. '2' > 1
        - true
    B. '2' < '12'
        - false
    C. 2 == '2'
        - true
    D. 2 === '2'
        - false
    E. true == 2
        - false
    F. true === Boolean(2)
        - true

15. Explain the difference between the == and === operators.
    - The == operator compares the values of two variables after performing type conversion if necessary. On the other hand, the === operator compares the values of two variables without performing type conversion.

17. If the function above is called with the following parameters modifyArray([1,2,3], doSomething), what will be the result? Briefly walk through how you arrived at that result.
    - [2, 4, 6]. Each number in array is multiplied by 2 and pushed to newArr. Since the reference does not change, const type is valid.

19. What is the output of the above code?
    ```
    1
    2
    3
    4
    ```


