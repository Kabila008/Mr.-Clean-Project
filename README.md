# Welcome to My Mr Clean
***

## Task
The problem is to retrieve and analyze content from a Wikipedia article about the "Ozone layer." 
The code should fetches the content, cleans it, tokenizes it, and then calculates the frequency of each word in the article. 

The challenges in this project include interacting with the Wikipedia API, handling and cleaning 
the retrieved data, and performing text analysis tasks like tokenization and word frequency counting.


## Description
Here's a step-by-step explanation of how the problem was solved in this code:
•	The get_content function retrieves the content of the Wikipedia article about the "Ozone layer" using the Wikipedia API.
•	The merge_contents function extracts and cleans the article text. It removes HTML tags and irrelevant sections from the content.
•	The tokenize function breaks the cleaned content into individual words (tokens) using regular expressions.
•	The lower_collection function converts all the tokens to lowercase to ensure consistency.
•	The count_frequency function counts the frequency of each token and stores it in a dictionary.
•	The print_most_frequent function takes the word frequencies, sorts them, and plots a horizontal bar chart to visualize the most common tokens in the article.
Stop words (common words like "the," "and," "in," etc.) are removed from the token collection to focus on meaningful words.


## Installation
This project doesn't require installation through npm or make; it's a Python script that can be 
executed directly on a Python environment. 
Ensure you have the required Python libraries (requests, re, and matplotlib) installed, which can typically be done using pip:
    pip install requests
    pip install matplotlib


## Usage
To use this code, follow these steps:
•	Ensure you have Python and the required libraries installed as mentioned above.
•	Copy and paste the provided Python code into a Python script file (e.g., my_mr_clean.py).
•	Execute the script using your Python interpreter.
•	The code will fetch the content of the "Ozone layer" Wikipedia article, clean it, tokenize it, and generate word frequency statistics.
•	The most common words in the article will be plotted in a horizontal bar chart, showing their frequencies.
•	Stop words will be removed, and another chart will display the most common meaningful words.
•	The results will be displayed in the console, and the charts will be shown in a graphical window.
This code can be adapted for other Wikipedia articles by changing the input to the get_content function to analyze different topics.
