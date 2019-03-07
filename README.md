
# Pig Latin Rules

input - string variable
output - updated string variable

#0 foreach words in the sentence do ->

#1  if input[0] == vowel then output = input + "way"

#2  else if input[0] == consonants then output = input[consecutive consonants - end] + input[0 - consecutive consonants] + "ay"

#3  else if input[0-1] == (qu) or input[0 - consonants].contains(qu) then output = input[consecutive consonants - end] + input[0 - qu] + "ay"

#4 else if input[0] == y then output = input[consecutive consonants - end] + input[0 - consecutive consonants] + "ay"



#Test Examples
#1
The program does nothing to non-alphabetical characters, since they do not contain consonants or vowels.
Example Input: 3
Example Output: 3

#2
The program adds "ay" to single-letter words beginning with a vowel.
Example Input: i
Example Output: iay

#3
The program adds "ay" to single-letter words beginning with a vowel.
Example Input: query
Example Output: eryqu

query  - uareq - eryqu
square - aresqu


quarts
