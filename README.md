# Project Title

Text mining and natural language processing

## Description
Text: https://www.gutenberg.org/cache/epub/72862/pg72862.txt

An important aspect to text mining and natural language processing is measuring word frequency and trends in word usage. This project deals with a simple exercise in loading a text file into Python and computing word frequency statistics and trends. It requires usage of text files, strings and dataframes.There are two importat txt files that we will be working with. The first file is WordText.txt which contains the actual text the program will be using. The second file is stop_words.txt which contain stops words that will be romved from the WordTxt.Txt during the excution. Stopwords are common words that appear in nearly every document and contribute little to the overall meaning. 
I will be working with the following  text :https://www.gutenberg.org/cache/epub/72862/pg72862.txt

This project consists of three parts.

IMPORTANT
Before starting these parts, it would very helpfull for you remove all special 
Use this website to remove all specail characters:
https://www.text-utils.com/remove-special-characters/

Part A:
In this part, we will load the entire text into a python list. 
After this step, we will print a dataframe with two columns, Word and Count. The Word column will display each word in the text and the Count column will dispaly the number of each word in the entire text. The words will be sorted in the order they appear in the WordText.txt file.

Part B:
In this part, we will creat modified version of the dataframe in part A. However, this dataframe will not contain any words listed in the stop_words.txt file. This modified version will be sorted by word count(Count) in decreasing order.

Par C:
In this part, we will be working with matplot to plot top six occuring words in the entire text. 
We want to calculate the ratio of each word appearances per chapter compared to the sum across in the entire text. We will express the ratio in in percentile. We will be working with max of five/5 chapters. 
We we will use six matplotlib plots to show trends for each to six words. 


## Getting Started

### Dependencies
NA
### Installing
Befor running this programe, ensure that your machine has the latest python version and anaconda. Ex:3.12.1

Please follow the following link for step by step on how to install anaconda
https://docs.anaconda.com/free/anaconda/install/windows/

Also follow the following link for step by step on how to install jupyter notebook within anaconda enviroment
https://test-jupyter.readthedocs.io/en/latest/install.html


You will also need to install the following liberies. 
Pandas for dataframe:
pip install pandas

matplotlib for graph:
pip install matplotlib

### Executing program
There are two files that you can run. 
Text_processor.py, Text_processor.ipynb
Both Text_processor.py, Text_processor.ipynb files will use WordText.txt and stop_words.txt

WordText.txt is the modified version of Catching_of_the_whale_and_seal.txt file. 
I removed everything before chapter 1 and used the first 5 chapters of the book. 
I also removed all special characters and any Illustration.

The two files are same depending on how you run one of the them. 
to run the file with .ipynb, 
Open your Anacoda Prompt, activate your enviroment, and type jyupter notebook.
This will open your files in browser. Navigate to where your Text_processor.ipynb and run it.

To run  Text_processor.py

Open a terminal of your choise. Gitbash is good one to use. 

Navigate to folder where Text_processor is located. 

Run the following command

Python nameofyourfile.py
Ex : Python Text_processor.py
This excute the whole file and open matplot window with six plots. 

The program will load lists, print dataframes, and display Matplotlib plots respectively.

Important note:
You might you run into the following warning:
"Pyarrow will become a required dependency of pandas in the next major release of pandas (pandas 3.0), (to allow more performant data types, such as the Arrow string type, and better interoperability with other libraries) but was not found to be installed on your system. If this would cause problems for you"

The reason this warning show up is becuase PyArrow will become a required dependency with pandas 3.0. 
Read the following link to learn more

https://pandas.pydata.org/docs/whatsnew/v2.1.0.html

To fix this warning, simply run the following command in your own anacoda enviroment(VS code):
pip install Pyarrow
    


## Authors

Elhacen Elmoustapha

## Version History
NA
## License
NA
## Acknowledgments
NA
