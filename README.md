# Algorithm-cp

Here's an algorithm that reads a sentence character by character and determines certain properties of the sentence:

1. Initialize an empty string variable called "sentence" to store the input sentence.
2. Read the input sentence character by character until a period (.) is encountered.
3. Append each character to the "sentence" variable.
4. Initialize an integer variable called "wordCount" to 0 to count the number of words in the sentence.
5. Initialize a boolean variable called "isUppercase" to true to track whether the sentence is entirely in uppercase.
6. Initialize a boolean variable called "containsDigit" to false to check if the sentence contains any digits.
7. Initialize a boolean variable called "endsWithExclamation" to false to determine if the sentence ends with an exclamation mark (!).
8. Initialize a boolean variable called "startsWithCapital" to false to check if the sentence starts with a capital letter.
9. Iterate through each character in the "sentence" variable:
    a. If the character is a space (' '), increment the "wordCount" variable.
    b. If the character is not uppercase, set the "isUppercase" variable to false.
    c. If the character is a digit, set the "containsDigit" variable to true.
10. Check the last character of the "sentence" variable:
    a. If it is an exclamation mark (!), set the "endsWithExclamation" variable to true.
    b. If it is a letter and uppercase, set the "startsWithCapital" variable to true.
11. Output the following properties of the sentence:
    a. The original sentence.
    b. The number of words in the sentence (wordCount + 1).
    c. Whether the sentence is entirely in uppercase (isUppercase).
    d. Whether the sentence contains any digits (containsDigit).
    e. Whether the sentence ends with an exclamation mark (endsWithExclamation).
    f. Whether the sentence starts with a capital letter (startsWithCapital).

Note: This algorithm assumes that the sentence ends with a single period (.) and does not include any other punctuation marks like question marks or commas.
