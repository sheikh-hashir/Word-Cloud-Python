# Word-Cloud-Python
The main purpose of this code is to create cloud consisting of words based on number of times they appeared in a file. The word that repeats the most will be shown bigger from the rest. 
First of all you have to use jupyter notebook for this code.
First of all there are some liberaries which you need to import for this code. 
Then there is a function named '_upload()', this function will create a button. Click on the button a select a text file. The name of the uploaded file is stored in filename.
Run this function is a separate section.

Then there is a fucntion named 'calculate_frequencies(file_contents):'. This function will calculate the frequencies of the words.
When the loop runs it takes a single character from the file and converts it into lower case and is checked if it is an alphabetical character or not. 
If it is an alphabetical character the character is appended to a string. 
If it is not an alphabetical character then the code will check whether the word is from the list of 'uninteresting_words',(this list contains the words which are commonly been used).
If it matches with any of the word from the list, thes string is set empty and the code runs agains until end of file character.
else it is checked that the word/key is already in the dictionary or not. 
If it is already in the dictionary than it the value increments by 1 else the value is set 1
Run this function is a separate section.

Display your cloud image by calling above function and you are done!!!
