
# Hashtag Analyzer

In this project we analyzes tweets from a CSV file and provides insights about a specific hashtag. It identifies the most common words used in tweets containing the hashtag and also retrieves a list of accounts that have used the hashtag. The code utilizes the Natural Language Toolkit (NLTK) library for text processing and analysis.

# Prerequisites

- Python 3.x
- NLTK library

      

## Installation
To use this script, please follow these steps:

1. Clone this repository to your local machine:

```bash
  git clone https://github.com/Amirrezahmi/Zozo-Assistant.git

```
2. Install the NLTK library by running the following command:
```bash
  pip install nltk
```
3. Download the required NLTK resources by executing the following code snippet:
```python
import nltk
nltk.download('stopwords')
nltk.download('averaged_perceptron_tagger')

```
# Usage
4. Ensure that you have a CSV file containing the tweets you want to analyze.
5. Open the script `hashtag_analyzer.py` in your preferred Python IDE or text editor.
6. Modify the following line of code to specify the path to your CSV file:
```python
with open('teet.csv', 'r', encoding='latin-1') as f:

```
7. Run the script.
8. When prompted, enter the hashtag you want to analyze (without the '#').
9. The script will perform the following tasks:
 - Extract all the words from the tweets that contain the specified hashtag.
 - Remove stop words and numbers from the list of words.
 - Classify each word as an adjective, verb, or other type of word.
 - Count the frequency of each word.
 - Return the top three most common words and their counts.
 - Find the accounts that use the specified hashtag.
10. The script will display the results in the console:
```bash
Three most repeated words:
<word1>: <count1>
<word2>: <count2>
<word3>: <count3>

List of accounts:
<account1>
<account2>
<account3>
...

```

# secreenshot
Here's an secreenshot of a sample example:

# Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1.  Fork the repository.
2. Create a new branch: git checkout -b my-new-branch.
3. Make your changes and commit them: git commit -m 'Add some feature'.
4. Push to the branch: git push origin my-new-branch.
5. Submit a pull request.
    
## License

This project is licensed under the [MIT License](https://opensource.org/license/mit/).

## Contact

For any questions or inquiries, please contact amirrezahmi2002@gmail.com

