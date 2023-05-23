#  Converts an int[] (array) to string.
-----------------------------------------------------
User story;
------------
An array  of ints say {4,1,3} should return {4,1,4}. Also, an array of ints say {6,9,9} should return {7,0,0}. 

The code's control flow is as follows;
---------------------------------------
1. A function takes in an array of integers as argument.
2. We convert to string using the string.Join("", num) method.
3. We then convert to integer using ConvertToIn32() method .
4. Next, we add 1 to the above converted number.
5. We convert back to string
6. We create an empty array, and then using a for loop, we push all members of the string into the array individually.

Author: Theophilus Unekwu Shaibu.
Date: 23/05/2023.
