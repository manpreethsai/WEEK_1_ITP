Problem 2:
------------------
Create an encrypter in python based on the ceaser cipher. It is a substitution cipher where each character of the original text is shifted a certain number characters in the alphabet. Write a function that would require 2 arguments – the input text to be encrypted and a key. For eg: Given the input text ‘hello’ and the key 3, the resulting encryted text would be ‘khoor’. Here you can see that every character in the string hello is shifted by 3 characters. ‘h’ has shifted to ‘k’, ‘e’ has shifted to ‘h’ and so on. If a key of 5 were used, the resulting string would be ‘mjqqt’. This function should be capable of ignoring any characters which are not alphabets. Th2 character ‘z’ entered b y the user for a key of 3 would result in ‘c’.

Usage:
encrypt(‘hello world!’, 3)
‘khoor zruog!’

Similarly create decrypter which can decode the encryted text when provided the input text and key

Usage:
decrypt(‘khoor zruog!’, 3)
‘hello world!’

For the sake of simplicity you can assume that input solely consists of lowercase alphabets, spaces and punctuation symbols. Numbers in the input text would also be ignored similar to symbols.

###########################################################################

  Rule to be followed

 1) Minimum 8 characters
 2) Should be a Alphanumeric(aleast one alphabet and one number)
 3) Should contain minimum 1 special Character -[!@#$%^&*]
 4) password should not be same as the username


 If password satisfies all the condition, print password is valid, if it not satisying, print the condition which are not satisfying.
 =======================================================================================

 Input : username : greatlearning
         password : abc1

 Output :
          Password is invalid
          Reason:
          Should contain minimum 8 characters
          Should contain minimum 1 special Character -[!@#$%^&*]

--------------------------------------------

 Input : username : greatlearning
         password : abc123@

 Output :
          Password is invalid
          Reason:
          Should contain minimum 8 characters

------------------------------------------------

 Input : username : greatlearning
         password : greatlearning

 Output :
          Password is invalid
          Reason:
          Should be a Alphanumeric(aleast one alphabet and one number)
          Should contain minimum 1 special