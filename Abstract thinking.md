## Task:

""A palindrome is a word that reads identically backward or forward. Consider the word `RACECAR`, what steps would you take to identify whether it was a palindrome? Write these down using concrete terms. Do the same for another word `DEFIED`.
Given the concrete examples, consider the generalized problem - informally describe an algorithm in English, that can identify any palindromes.""

## My answer

For the word `RACECAR`, to identify it as a palindrome,
 * First, count how many letters are in the word. You should find that `RACECAR` has an odd number of letters therefore, the middle letter which is `e` does not need to be looked at. 
 * Secondly, look at the *first* letter of the word and the *last* letter and check if they are the same. Due to the fact that they are both the letter `R`, the word could still be a palindrome.
 * Thirdly, check the *second* letter and the *second* to last letter to see if they are the same.
 * Then, repeat these these steps, doing the next pairs of letters until every pairs of letters have ben checked.
 * Finally, once you have covered all the letters you should find that every pair of letters in the word match which means that the word `RACECAR` is a palindrome.

The same rules could apply for the word `DEFIED` to check if it is a palindrome. The only exception is that the word has an even number of letters so, all letters will have to be checked:
 * First, count how many letters are in the word. You should find that `DEFIED` has an even number of letters therefore, all letters will have to be checked. 
 * Secondly, look at the *first* letter of the word and the *last* letter and check if they are the same. Due to the fact that they are both the letter `D`, the word could still be a palindrome.
 * Thirdly, check the *second* letter and the *second* to last letter to see if they are the same.
 * Then, repeat these these steps, doing the next pairs of letters until every pairs of letters have ben checked.
 * Finally, once you have covered all the letters you should find that the pair of letters `F` and `E` do not match which means that the word `DEFIED` is not a palindrome.

The same rules could apply for any other word to check if it is a palindrome:
 * First, count how many letters are in the word. If they are even, you need to check every pair of letters in the word. If it is odd, you have to check every pair of letters in the word and ignore the middle letter to identify it as a palindrome.
 * Secondly, look at the *first* letter of the word and the *last* letter and check if they are the same. At any point, if any pairs of letters are not the same, you can stop can identify the word as 'not a palindrome'.
 * Thirdly, check the *second* letter and the *second* to last letter to see if they are the same.
 * Then, repeat these these steps, doing the next pairs of letters until every pairs of letters have ben checked.
 * Finally, once you have covered all the letters (ignoring the middle letter if there is one), if all of the pairs match, then the word is a palindrome.
