# This is the Final Project completed as part of the CSC 113 Course
### By: Ayan Das, Adeeb Ahmed, Nasif Rahman

<p><b>Purpose:</b> This project contains two features. The first part of the project involves implementing a function that will analyze a text file and output in the form of a dictionary the words and the frequency at which they appear throughout the text. The keys being the unique words itself and the associated values representing the integer value, which indicates the number of times the associated word appear throughout the text.</p>

<br>

<p>For our source of data, we used the website: https://www.gutenberg.org/ebooks/69079, this link contains the source where the text file was downloaded. It was an ebook and had various download options, so we went with the text file option since that was the requirement of the project prompt. Prior to running the function "wordFrequency", we needed to retrieve the text file from our storage and convert it into a string, removing any line breaks and splits so we can traverse the string. We also needed a dictionary to serve as a container for the word frequency.</p>

<p><b> This project was split into two parts:</p></b>
- Calculate the word frequency based on a text file as well as the most frequent word
- Implement either multithreading/multiprocessing to observe the runtime execution

#### Role Distribution:

Nasif: Implemented the "wordFrequency()" function that takes in one parameter and outputs a dictionary where the keys represents the word and the values represent the frequency. He also implemented thread 3 and 4.

Adeeb: Implemented the "HighestWordFrequency()" function that outputs the word that appears the most frequently as well as the number of times the word appears throughout the text file.

Ayan: Implemented the multithreading for threads 5-8 as well as implementing the visualization for runtime execution for threads 2-8 using matplotlib and wrote the readMe file with instructions on how to run the program.

Note: When you open up the program, you will also have to install the text file within the repository, copy the file path (because the file path we used may differ from the file path someone else use, depending on where the text file in the local machine was stored), so the path needs to be adjusted appropriately, otherwise, you will get an error, and ensure the dictionary you use, if you choose to use a different dictionary, change it to "defaultdict" type. Other than that, you can go through the ipnyb file and the code will work as intended, without any syntax based errors.


