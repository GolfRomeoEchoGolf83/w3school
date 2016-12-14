# 25 days of W3SCHOOL PHP Challenges
1. [] Write a PHP program to check if a given positive integer is a power of two. 

Input : 4
Output :4 is power of 2 


2. [] Write a PHP program to check if a given positive integer is a power of three. 

Input : 9
Output : 9 is power of 3

3. [] Write a PHP program to check if a given positive integer is a power of four. 

Input : 4
Output : 4 is power of 4

4. [] Write a PHP program to check if an integer is the power of another integer. 

Input : 16, 2
Output : 16 is power of 2
Example: For x = 16 and y = 2 the answer is "true", and for x = 12 and y = 2 "false"

5. [] Write a PHP program to find a missing number(s) from an array.

Input : 1,2,3,6,7,8
Output : Array 

( 
[3] => 4
[4] => 5
) 

6. [] Write a PHP program to find three numbers from an array such that the sum of three consecutive numbers equal to zero.Go to the editor

Input : (-1,0,1,2,-1,-4)
Output : Array 

( 
[0] => -1 + 0 + 1 = 0 
) 

7. [] Write a PHP program to find three numbers from an array such that the sum of three consecutive numbers equal to a given number.

Input : (array(2, 7, 7, 1, 8, 2, 7, 8, 7), 16))
Output : Array 

( 
[0] => 2 + 7 + 7 = 16
[1] => 7 + 1 + 8 = 16
)

8. [] Write a PHP program to compute and return the square root of a given number. Go to the editor

Input : 16
Output : 4

9. [] Write a PHP program to find a single number in an array that doesn't occur twice. Go to the editor

Input : array(5, 3, 4, 3, 4)
Output : Array 

( 
[0] => 5 
[1] => 3 
[2] => 4 
[3] => 3 
[4] => 4 
) 
Single Number: 5 

10. [] Write a PHP program to find the single element in an array where every element appears three times except for one.Go to the editor

Input : array(5, 3, 4, 3, 5, 5, 3)
Output : Array 

( 
[0] => 5 
[1] => 3
[2] => 4 
[3] => 3 
[4] => 5
[5] => 5 
[6] => 3 
) 

Single Number: 4 

11. [] Write a PHP program to find the single element appears once in an array where every element appears twice except for one. Go to the editor

Input : array(5, 3, 0, 3, 0, 5, 7, 7, 9)
Output : 9

12. [] Write a PHP program to add the digits of a positive integer repeatedly until the result has a single digit.Go to the editor
For example given number is 59, the result will be 5.

Input : 48
Output : 3 
Step 1: 5 + 9 = 14
Step 1: 1 + 4 = 5

13. [] Write a PHP program to reverse the digits of an integer.Go to the editor

Sample :
x = 234, return 432
x = -234, return -432
Click me to see the sample solution

14. [] Write a PHP program to reverse the bits of an integer (32 bits unsigned). Go to the editor

Input : 1234
Output: 1260388352
For example, 1234 represented in binary as 10011010010 and returns 1260388352 which represents in binary as 1001011001000000000000000000000.

15. [] Write a PHP program to check a sequence of numbers is an arithmetic progression or not. Go to the editor
In mathematics, an arithmetic progression or arithmetic sequence is a sequence of numbers such that the difference between the consecutive terms is constant.

Input : array(5, 7, 9, 11)
Output : An arithmetic sequence
For example, the sequence 5, 7, 9, 11, 13, 15 ... is an arithmetic progression with common difference of 2.

16. [] Write a PHP program to check a sequence of numbers is a geometric progression or not. Go to the editor

Input : array(2, 6, 18, 54)
Output : Geometric sequence
In mathematics, a geometric progression or geometric sequence, is a sequence of numbers where each term after the first is found by multiplying the previous one by a fixed, non-zero number called the common ratio. For example, the sequence 2, 6, 18, 54, ... is a geometric progression with common ratio 3. Similarly, 10, 5, 2.5, 1.25, ... is a geometric sequence with common ratio 1/2.
Click me to see the sample solution

17. [] Write a PHP program to compute the sum of the two reversed numbers and display the sum in reversed form. Go to the editor

Input : 13, 14
Output : 72
Note : The result will not be unique for every number for example 31 is a reversed form of several numbers of 13, 130, 1300 etc. Therefore all the leading zeros will be omitted.

18. [] Write a PHP program where you take any positive integer n, if n is even, divide it by 2 to get n / 2. If n is odd, multiply it by 3 and add 1 to obtain 3n + 1. Repeat the process until you reach 1. Go to the editor

Input : 12
Output : Array 

( 
[0] => 12
[1] => 6 
[2] => 3 
[3] => 10
[4] => 5 
[5] => 16
[6] => 8 
[7] => 4 
[8] => 2 
[9] => 1 
)

According to Wikipedia the Collatz conjecture is a conjecture in mathematics named after Lothar Collatz, who first proposed it in 1937. The conjecture is also known as the 3n + 1 conjecture. 
The conjecture can be summarized as follows. Take any positive integer n. If n is even, divide it by 2 to get n / 2. If n is odd, multiply it by 3 and add 1 to obtain 3n + 1. Repeat the process (which has been called "Half Or Triple Plus One") indefinitely. The conjecture is that no matter what number you start with, you will always eventually reach 1.
Example :
For instance, starting with n = 12, one gets the sequence 12, 6, 3, 10, 5, 16, 8, 4, 2, 1.
n = 19, for example, takes longer to reach 1: 19, 58, 29, 88, 44, 22, 11, 34, 17, 52, 26, 13, 40, 20, 10, 5, 16, 8, 4, 2, 1.

19. [] Write a PHP program to check whether a given number is an ugly number. Go to the editor

Input : 12
Output :12 is an Ugly number 

Ugly numbers are positive numbers whose only prime factors are 2, 3 or 5. The sequence 1, 2, 3, 4, 5, 6, 8, 9, 10, 12, ...
shows the first 10 ugly numbers. 
Note: 1 is typically treated as an ugly number.

20. [] Write a PHP program to get the Hamming numbers upto a given numbers also check whether a given number is an Hamming number. Go to the editor

Input : 1
Output : Hamming Number 
In mathematics, an arithmetic progression or arithmetic sequence is a sequence of numbers such that the difference between the consecutive terms is constant.
For example, the sequence 5, 7, 9, 11, 13, 15 ... is an arithmetic progression with common difference of 2.

21. [] Write a PHP program to check if a given string is an anagram of another given string. Go to the editor

Input : ('anagram','nagaram')
Output : These two strings are anagram
According to Wikipedia, an anagram is direct word switch or word play, the result of rearranging the letters of a word or phrase to produce a new word or phrase, using all the original letters exactly once; for example, the word anagram can be rearranged into nag-a-ram.

22. [] Write a PHP program to push all zeros to the end of a array. Go to the editor

Input : array(0,2,3,4,6,7,10)
Output : Array 

( 
[0] => 2
[1] => 3
[2] => 4
[3] => 6
[4] => 7
[5] => 10
[6] => 0 
) 

23. [] Write a PHP program to find majority element in an array. Go to the editor

Input : array(1, 2, 3, 4, 5, 5, 5, 5, 5, 5, 6)
Output : 5
Note: The majority element is the element that appears more than n/2 times where n is the number of elements in the array.

24. [] Write a PHP program to find the length of the last word in a string. Go to the editor

Input : PHP Exercises
Output : 9

25. [] Write a PHP program to find the single number which occurs odd numbers and other numbers occur even number. Go to the editor

Input : 4, 5, 4, 5, 2, 2, 3, 3, 2, 4, 4
Output : 2
