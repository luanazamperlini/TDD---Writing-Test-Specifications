# TDD-Writing-Test-Specifications

# Prompts: 
### For each prompt below: 

- Read the prompt.
- Identify the expectations.
- Write specifications in pseudocode/plain English for all the tests that would be useful for that prompt.
- Try to take any "edge cases," or unexpected circumstances, into account, and write test specs for them.
- Try not to write extraneous tests!


# Unit Tests:

- A function called "multiplication" that returns the product of the two input numbers.
### Create a function that accepts "a" and "b" and returns the mulltiplication of both numbers.

- A function called "concatOdds" takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending order, from both of the arrays.
### The code should loop through the two arrays to select only the odd numbers from the input interegers and organize them all on a ascenging order, avoiding repeating the numbers that are the same in both arrays. 

### expect a function concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) and it should result in [-1, 1, 3, 9, 15]
- Example: concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) ...should result in [-1, 1, 3, 9, 15]
- Think about the following; you may need to make assumptions or decisions about the prompt and how the code should behave:
  
## the first number of the first arr will be multiplied by the first, second, third... numbers of the second array.
## the sencond number of the first arr will be multiplied by the first, second, third... numbers of the second array.
## the third number of the first arr will be multiplied by the first, second, third... numbers of the second array.
#### 27, 3, 3, 3, 12, 45, -3
#### 18, 2, 2, 2, 8, 30, -2
#### 9, 1, 1, 1, 4, 15, -1

## the code will print only the result of the five first numbers starting on -1.
## should return a new array [-1, 1, 3, 9, 15].

- What should happen with unexpected inputs?
## unexpected inputs will be ignored.

- What kinds of unexpected inputs should we worry about?
## we consider unexpected inputs numbers less than -1, even numbers, repeated numbers that should not be printed twice. 

- What should happen when there are multiples of the same odd number in the arrays?
## the even numbers should not be printed on the result

###### (Hint: We gave you the answer to this one in the example above.)


# Functional Tests:
- A shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest.
##

- Think about the following; you may need to make assumptions or decisions about the prompt and how the feature should behave:
##

- What should happen if the cart is empty?

##
- What needs to be shown to the user at each step of check out?
##

- What behaviors of this feature does the prompt miss or gloss over?
##

###### Hint: Observe the shopping cart and checkout features of some popular websites to get some ideas!


