# Python-Assignments

1. Write a Python program to find the length of a string.
Input Hello World
Expected Output Length = 11


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

in[]

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


###Write a Python program to check whether a string is a palindrome or not. Input madam Expected Output The string is a palindrome
            
input_string = "madam"
cleaned_string = input_string.lower()

if cleaned_string == cleaned_string[::-1]:
    print("The string is a palindrome")
else:
    print("The string is not a palindrome")

    ------>The string is a palindrome


    ######4.  Write a Python program to convert a string to uppercase and lowercase. 
    #Input LihaTech Expected 
    #Output Uppercase = LIHATECH Lowercase = lihatech


    input_string = "LihaTech"

uppercase_string = input_string.upper()
lowercase_string = input_string.lower()

print(f"Uppercase = {uppercase_string} Lowercase = {lowercase_string}")

---> Uppercase = LIHATECH Lowercase = lihatech

#####5.  Write a Python program to count the number of words in a sentence. 
#Input Python is easy to learn 
#Expected Output Word count = 5

input_string = "Python is easy to learn"
words = input_string.split()
word_count = len(words)

print(f"Word count = {word_count}")

----->Word count = 5

#####6.  Write a Python program to reverse a given string.
# Input Python Expected
#Output Reversed string = nohtyP

input_string = "Python"
reversed_string = input_string[::-1]

print(f"Reversed string = {reversed_string}")

---->Reversed string = nohtyP


######7.  Write a Python program to check whether two strings are anagrams. 
#Input listen silent Expected
# Output The strings are anagrams.

string1 = "listen"
string2 = "silent"

if sorted(string1) == sorted(string2):
    print("The strings are anagrams.")
else:
    print("The strings are not anagrams.")

    ---->The strings are anagrams.


