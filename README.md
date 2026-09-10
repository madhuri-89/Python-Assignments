# Python-Assignments

1. Write a Python program to find the length of a string.
Input Hello World
Expected Output Length = 1


a = "hello world"
length = len(a)
print("Length =", length)
--> length = 11

   #another way
   
l = "hello world"
length = len(l)
print(length)
--> 11

#2. Write a Python program to count vowels and consonants in a string.
#Input Programming
#`Expected Output Vowels = 3, Consonants =8

text = "Programming"
vowels_set = set("aeiouAEIOU")
vowels = 0
consonants = 0

for char in text:

    if char.isalpha():                                     #char.isalpha():ensures onlyalphabetic characters are counted, safely ignoring any punctuation

       if char in vowels_set:                              #char in vowels_set: checks if letter is a vowel;otherwise counted as a consonant
          vowels += 1

       else: 
            consonants += 1

print(f"vowels = {vowels}, consonants = {consonants}")
--> vowels = 3 , consonants = 8

