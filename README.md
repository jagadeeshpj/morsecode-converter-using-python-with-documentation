![transulatator rxe](https://user-images.githubusercontent.com/87519174/129375357-030b957b-d65d-4c80-9201-03e201f5172a.JPG)



# morsecode converter using python with documentation
Morse code is a method of transmitting text information as a series of on-off tones, lights, or clicks that can be directly understood by a skilled listener or observer without special equipment. It is named for Samuel F. B. Morse, an inventor of the telegraph.

Algorithm-: The algorithm is very simple. Every character in the English language is substituted by a series of ‘dots’ and ‘dashes’ or sometimes just singular ‘dot’ or ‘dash’ and vice versa.

Encryption

1-In case of encryption we extract each character (if not a space) from a word one at a time and match it with its corresponding morse code stored in whichever data structure we have chosen(if you are coding in python, dictionaries can turn out to be very useful in this case)

2-Store the morse code in a variable which will contain our encoded string and then we add a space to our string which will contain the result.

3-While encoding in morse code we need to add 1 space between every character and 2 consecutive spaces between every word.

4-If the character is a space then add another space to the variable containing the result. We repeat this process till we traverse the whole string.

Decryption

1-In case of decryption, we start by adding a space at the end of the string to be decoded.

2-Now we keep extracting characters from the string till we are not getting any space.

3-As soon as we get a space we look up the corresponding English language character to the extracted sequence of characters (or our morse code) and add it to a variable which will store the result.

4-Remember keeping track of the space is the most important part of this decryption process. As soon as we get 2 consecutive spaces we will add another space to our variable containing the decoded string.

5-The last space at the end of the string will help us identify the last sequence of morse code characters (since a space acts as a check for extracting characters and start decoding them)

Implementation-: Python provides a data structure called dictionary which stores information in the form of key-value pairs which is very convenient for implementing a cipher such as the morse code. We can save the morse code chart in a dictionary where (key-value pairs) => (English Characters-Morse Code). The plaintext (English characters) take the place of keys and the ciphertext (Morse code) form the values of the corresponding keys. The values of keys can be accessed from the dictionary in the same way we access the values of an array through their index and vice versa.

MODULES USED

dictionary.py :- This module consists of a morse code dictionary having keys and values for the conversion.

encryption.py :- This module consists of a function which is used to convert normal text into morse code.

decryption.py :- This module consists of a function which is used to convert morse code into plain text.

gui.py :- This is the module where you can run the code with its simple GUI interface.

gui_support.py :- This is module with try and except for importing the right library and for displaying GUI.

run.py :- This module deals with running of code with GUI. It is terminal based for the sake of simplicity.


FOR CONVERTING PYTHON FILE  TO EXE 

MODULES USED
* pyinstaller.py
* .ico  {image format}

SPECIALLY   UPLOADED THE DOCUMENTATION OF THIS PROJECT FOR UR REFERENCE😊😊😊😊😊😊


PLEASE SHARE AND SUPPORT
❤❤❤
