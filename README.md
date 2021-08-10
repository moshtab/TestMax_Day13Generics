# TestMax_Day13Generics
UC1 :- Given 3 Integers find the maximum

 - Ensure to test code with the Test Case.
 
 - To ensure your Code works you need 3 test cases with Max Number at 1st, 2nd and 3rd

 - Use Integer Object and compareTo method to test the maximum number

UC2 :- Given 3 Floats find the maximum

UC3 :- Given 3 Strings find the maximum

Refactor1 :-Refactor all the 3 to One Generic Method and find the maximum

- Ensure the Generic Type extend Comparable 
  
  - Make the test case work

Refactor2 :-Refactor to create Generic Class to take in 3 variables of Generic Type
 - Ensure the Generic Type extends Comparable
 
- Write parameter constructor

- Write testMaximum method to internally call the static testMaximum method passing the 3 instance variables

- Define new test case to use the Generic Class

UC4 :-Extend the max method to take more then three parameters 

-sorting

UC5 :-Extend the max method to also print the max to std outusing Generic Method 
 
 - Write printMax Generic Method which is  internally called from testMaximum
