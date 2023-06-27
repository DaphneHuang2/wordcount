# wordcount
Explanation:
This code implements a program to count the frequency of each word in a given text. The frequency of a word refers to the number of times it appears in the text.

The count_word_frequency function takes a parameter text, which is the input text to analyze, and performs the following steps:

It converts the text to lowercase using the lower() method to ensure case-insensitive counting.
It splits the text into individual words using the split() method, which splits the text at whitespace.
It initializes an empty dictionary called frequency to store the word frequencies.
It iterates over each word in the words list.
For each word, it checks if it already exists in the frequency dictionary.
If the word is already a key in the dictionary, it increments its corresponding value (frequency) by 1.
If the word is not yet a key in the dictionary, it adds it as a new key with a value of 1.
Finally, it returns the frequency dictionary containing the word frequencies.
In the main part of the code, the user is prompted to enter a text. The input is stored in the input_text variable.
The count_word_frequency function is called with the input_text as an argument to count the word frequencies. The resulting frequencies are stored in the word_frequency dictionary.
The program then prints the word frequencies by iterating over the items of the word_frequency dictionary. Each word and its corresponding count are displayed.

Please note that this code treats punctuation and special characters as part of the words. Depending on the specific requirements, additional preprocessing or handling may be needed to exclude or handle such characters.
