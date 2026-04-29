1. Since i was declared outside of the block where it is printed, this will throw an error
2. 150, it will print due to the work done on it in the for loop, and since it is declared with var which has function scope
3. 150, since it was declared with var it has function scope
4. [50, 100, 150], since each value is just rounded, and then added to the list
5. i is defined using a let, meaning it has block scope, so it is not known after the for loop, so this will throw an error
6. This will throw an error because it was defined using a let within the for loop block, so it is not known after the block
7. 150. No error is thrown because it was defined using a let with function scope
8. [50, 100, 150] since all variables are available in function scope
9. There will be an error because i is definined with a let inside the loop scope, and so outside of the loop trying to print i will throw an error
10. 3, no error since const has block scope, which in this case is the function scope so it is available to be used everywhere in the function
11. [50, 100, 150], it is available through out the function due to its scope and the code loops through the prices and applies the discount to edit the values
12 A. student.name
12 B. student['Grad Year']
12 C. student.greeting()
12 D. student['Favorite Teacher].name
12 E. student.courseLoad[0]
13 A. '32' because it string concates
13 B. 1 since minus forces num comparison
13 C. 3 since null is viewed as 0
13 D. '3null' since string concatentation
13 E. 4 since true is viewed as value 1
13 F. 0 since false = 0 and null = 0 so 0
13 G. '3undefined' since string concatention
13 H. Nan since it tries to do num comparison and this leads to undefined behavior
14 A. true, since num comparison 
14 B. false since lexigrophic comparison
14 C. true since loose comparison since checks equality of ints
14 D. false since strict comparison and these are different types
14 E. false since true = 1 and 1 not equal 2
14 F. true since Boolean(2) leads to value true and these are equal
15. == is a loose comparison so it can change types and check equality, however === is strict and they must be the same type and value
16. 
17. [2, 4, 6 ]The function creates a new array and for every element in the parameter it applies the call back (which multiplies the number 2) and then adds it to the new array and returns that array
18. 
19. 1, 4, 3, 2 with lines in between each. This happens because the two with out timeouts are printed first, then the timeout with 0 sec next, and the 1 sec after that
