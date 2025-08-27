# INTRODUCTION TO PYTHON PROGRAMMING
## ALPHABET SOUP PROBLEM: 
Create a function that takes a string and returns a string with its letters in alphabetical order.

Example:

alphabet_soup(“hello”) ➞ ehllo

alphabet_soup(“hacker”) ➞ acehkr
<img width="1141" height="292" alt="image" src="https://github.com/user-attachments/assets/c90a12eb-17de-4e35-b1d0-905847cbb013" />
In creating the code for the Alphabet Soup problem, I created a function [alphabet_soup] that takes a string as an input and arranges its letters alphabetically. Within the function, the sorted() function is used for the purpose of arranging the letters, while the join() function is for the purpose of combining the letters back into a single string. The print() function is then used to display the results after arranging and combining the letters back together of a given string. After testing it with example strings like “hello” and “hacker”, the results of the code came out as “ehllo” and “acehkr”, which confirmed that the code is working.

## EMOTICON PROBLEM: 
Create a function that changes specific words into emoticons. Given a sentence as a string, replace the words smile, grin, sad and mad with their corresponding emoticon:

Example:

emotify(“Make me smile”) ➞ Make me :)

emotify(“I am mad”) ➞ I am >:(
<img width="1028" height="435" alt="image" src="https://github.com/user-attachments/assets/b6050de5-2a3b-4d6e-97d2-a9d5ede6628c" />
For this code, the defined "emotify" function is responsible for taking a sentence and converting certain words; "smile", "grin", "sad", and "mad", into emoticons. I used a dictionary to store word–emoticon pairs, which made it easy to map each word to its corresponding symbol or face. Then, I applied the for loop to go through every key–value pair in the dictionary and used the replace() function to substitute the matching word in the sentence with its emoticon. I also added replace(word.capitalize(), symbol) to the code so that it would not be case-sensitive even when small and capitalized words are used and that it will be detected and replaced correctly. Finally, the print() function was used to display the transformed sentences.

## UNPACKING LIST PROBLEM:
Unpack the list writeyourcodehere into three variables, being first, middle, and last, with middle being everything in between the first and last element. Then print all three variables.

Example: 

lst = [1, 2, 3, 4, 5, 6]

Output: first: 1 middle: [2,3,4,5] last: 6
<img width="1138" height="309" alt="image" src="https://github.com/user-attachments/assets/a96903e1-843a-4cb4-a60d-2186c39d160f" />
[explanation]
