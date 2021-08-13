## Task:

"A palindrome is a word that reads identically backward or forward. Consider the word “RACECAR”, what steps would you take to identify whether it was a palindrome? Write these down using concrete terms. Do the same for another word “DEFIED”.
Given the concrete examples, consider the generalized problem - informally describe an algorithm in English, that can identify any palindromes."

For the word "Racecar", to identify if it is a palindrome:
 * First, look at the *first* letter of the word and the *last* letter and check if they are the same. Due to the fact that they are both the letter 'R', the word could still be a palindrome.
 * Next, check the *second* letter and the *second* to last letter to see if they are the same.
 * Thirdly, repeat these these steps as you get closer to the middle of the word.
 * Racecar has an odd number of letters therefore, the middle letter which is "e" does not need to be checked.
 * Once you have covered all the letters you should find that every pair of letters in the word match which mean that the word 'racecar' is a palindrome
