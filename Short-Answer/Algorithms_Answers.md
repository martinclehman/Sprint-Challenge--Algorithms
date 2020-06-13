#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) - while loop will take n times n^2 to reach while loop condition of n^3


b) O(n^2) - outer loop will take O(n), inner loop takes O(n/2). Multiplying together and considering rounding order we obtain O(n^2/2)->O(n^2) 


c) O(n) - each call to function takes O(1) but recursion dictates n calls to function

## Exercise II

Apply a binary search approach using iterative approach:

Drop egg at half of n-story building:
 - if breaks: re-do experiment half-way below
 - if doesn't break: re-do experiment half-way above
 - continue until floor level of break and not breaking is found

Runtime Complexity: O(log n)


