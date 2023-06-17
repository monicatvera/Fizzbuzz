# Kata FizzBuzz
The typical statement of the kata says: write a program that displays the numbers from 1 to 100, replacing the multiples of 3 with the word "fizz" and, in turn, the multiples of 5 with "buzz". For numbers that are multiples of 3 and 5, we will use the string "fizzbuzz".

What we are going to do is create a pure function that transforms the numbers to string and returns fizz, buzz or fizzbuzz as appropriate. At first we will skip the part of generating the numbers from 1 to 100.

## Test list
  Before facing the implementation of the problem, the first thing we are going to do is a list of tests to be clear about the different cases that we must take into account.

  - [x] For the number 1 the result must be "1".
  - [x] For number 3 the result should be "fizz"
  - [x] For number 5 the result should be "buzz"
  - [x] For number 15 the result should be “fizzbuzz”
  - [x] For any number divisible by 3 the result must be "fizz"
  - [x] For any number divisible by 5 the result must be "buzz"
  - [x] For any number divisible by 15 the result must be "fizzbuzz"
  - [x] For the rest of the numbers the result should be the received number itself