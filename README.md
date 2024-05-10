This project was completed by one student (there was a group option available).
The project objective is to implement 4 programmer defined functions 
with use of loops, arrays, and c- style strings.
The program declares character arrays (inputWord, upperWord, hashWord, and originalWord) 
to hold original and modified versions of the input word. 
It then implements a do/while loop: prompts user to input a word, makes a copy of it, and modifies it.
After displaying the original and modified input, it asks if user wants to enter another word or quit program.
SophieGetInput Function: Asks user to input a word, without spaces, stores it in inputWord.
SophieMakeUpper Function: Takes user's input, creates all-uppercase version of it.
SophieHashtag Function: Converts uppercase word so all vowels are # and consonants are ~.
SophieCompund Function: Concatenates original input word, all-uppercase word, and #/~ word into one string. 
Uses strcat function to append upperWord and hashWord to inputWord, storing result in inputWord. 
After processing, original input word, uppercase version, #/~ version, and the final concatenated result are printed.

To compile, build, and execute an interactive program using functions from stdio.h (printf and 
scanf), ctype.h, and string,h. A  loop, character arrays and  programmer defined functions with pass by copy 
(input) parameters and pass reference  (input/output) character array parameters.  
