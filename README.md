# JS-challenger


1.// ! Write a function which calculates the average of the numbers in a given list.

//! Note: Empty arrays should return 0.

![image](https://user-images.githubusercontent.com/109246384/191336378-30213a7b-7560-4bbd-928b-7287934b07bd.png)


2.//! An isogram is a word that has no repeating letters, consecutive or non-consecutive. Implement a function that determines whether a string that contains only letters is an isogram. Assume the empty string is an isogram. Ignore letter case.

![image](https://user-images.githubusercontent.com/109246384/191354913-8206b813-071d-408a-b6c1-7b8a1c965367.png)


3.//! Implement the function unique_in_order which takes as argument a sequence and returns a list of items without
//! any elements with the same value next to each other and preserving the original order of elements.


![image](https://user-images.githubusercontent.com/109246384/191358631-25a2e4fe-4a41-459d-924b-4fb9b8ce205a.png)



4.// !! Deoxyribonucleic acid (DNA) is a chemical found in the nucleus of cells and carries the "instructions" for the development and functioning of living organisms.

// !!If you want to know more: http://en.wikipedia.org/wiki/DNA

//!! In DNA strings, symbols "A" and "T" are complements of each other, as "C" and "G". Your function receives one side of the DNA (string, except for Haskell); you need to return the other complementary side. DNA strand is never empty or there is no DNA at all (again, except for Haskell).

// !!More similar exercise are found here: http://rosalind.info/problems/list-view/ (source)

//!! Example: (input --> output)

//!! "ATTGC" --> "TAACG"

![image](https://user-images.githubusercontent.com/109246384/191364122-013af047-511f-4cc7-8d4a-83ab8688d1e3.png)


5. //#Find the missing letter

Write a method that takes an array of consecutive (increasing) letters as input and that returns the missing letter in the array.

You will always get an valid array. And it will be always exactly one letter be missing. The length of the array will always be at least 2.
The array will always contain letters in only one case.

Example:

['a','b','c','d','f'] -> 'e' ['O','Q','R','S'] -> 'P'

![image](https://user-images.githubusercontent.com/109246384/191372909-b7dd1c16-bf90-4bae-a3bf-a1c8cd5c245f.png)

6.// You probably know the "like" system from Facebook and other pages. People can "like" blog posts, pictures or other items. We want to create the text that should be displayed next to such an item.

// Implement the function which takes an array containing the names of people that like an item. It must return the display text as shown in the examples:

// []                                -->  "no one likes this"
// ["Peter"]                         -->  "Peter likes this"
// ["Jacob", "Alex"]                 -->  "Jacob and Alex like this"
// ["Max", "John", "Mark"]           -->  "Max, John and Mark like this"
// ["Alex", "Jacob", "Mark", "Max"]  -->  "Alex, Jacob and 2 others like this"
// Note: For 4 or more names, the number in "and 2 others" simply increases.

![image](https://user-images.githubusercontent.com/109246384/191861604-616f9448-0c19-4bce-b161-7e1954c62b63.png)


7.// '(', '{', '[' are called "openers."
// ')', '}', ']' are called "closers."
// Write an efficient function that tells us whether or not an input string's openers and closers are properly nested.

// Examples:

// "{ ( )[ ]  }" should return true
// "{ [ ( ] ) }" should return false
// "{ [ }" should return false
// Simply making sure each opener has a corresponding closer is not enough???we must also confirm that they are correctly ordered.
// For example, "{ [ ( ] ) }" should return false, even though each opener can be matched to a closer.




![image](https://user-images.githubusercontent.com/109246384/192039478-b424c5e4-eaad-47ad-87b3-0f1a7492aa4b.png)


8. // Given an array of integers, find the one that appears an odd number of times.

// There will always be only one integer that appears an odd number of times.

// Examples
// [7] should return 7, because it occurs 1 time (which is odd).
// [0] should return 0, because it occurs 1 time (which is odd).
// [1,1,2] should return 2, because it occurs 1 time (which is odd).
// [0,1,0,1,0] should return 0, because it occurs 3 times (which is odd).
// [1,2,2,3,3,3,4,3,3,3,2,2,1] should return 4, because it appears 1 time (which is odd).

![image](https://user-images.githubusercontent.com/109246384/192051335-aa52b5bd-2da2-4472-8364-730510c050e1.png)


9.// If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.

// Finish the solution so that it returns the sum of all the multiples of 3 or 5 below the number passed in. Additionally, if the number is negative, return 0 (for languages that do have them).

// Note: If the number is a multiple of both 3 and 5, only count it once.
![image](https://user-images.githubusercontent.com/109246384/192054831-5933b501-4d70-4362-ac9b-8aa9e4effc6d.png)


10.// You live in the city of Cartesia where all roads are laid out in a perfect grid. 
// You arrived ten minutes too early to an appointment, so you decided to take the opportunity to go for a short walk. 
// The city provides its citizens with a Walk Generating App on their phones -- everytime you press the button it sends you an array of one-letter strings representing directions to walk (eg. ['n', 's', 'w', 'e']). 
// You always walk only a single block for each letter (direction) and 
// you know it takes you one minute to traverse one city block, so create a function that will return true 
// if the walk the app gives you will take you exactly ten minutes (you don't want to be early or late!) and will, of course, return you to your starting point.
//  Return false otherwise.

![image](https://user-images.githubusercontent.com/109246384/192058838-b32b01bc-aa45-4f5b-a9fd-1be83ed38548.png)


11.Your task, is to create NxN multiplication table, of size provided in parameter.

for example, when given size is 3:

1 2 3
2 4 6
3 6 9
for given example, the return value should be: [[1,2,3],[2,4,6],[3,6,9]]

![image](https://user-images.githubusercontent.com/109246384/193689287-f6af392d-0c2d-4eeb-922b-1ffafb090c49.png)



