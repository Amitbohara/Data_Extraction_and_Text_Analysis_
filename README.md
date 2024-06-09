# data_Extraction_and_Text_Analysis_

Data Extraction and NLP Project
Project Title: Data Extraction and NLP for Article Analysis

Objective:
The goal of this project was to extract textual data from given URLs, perform comprehensive text analysis, and compute various linguistic and readability metrics. The results were formatted and saved according to a specified structure.

Technologies Used:

Python
Pandas
Requests
BeautifulSoup
NLTK
OpenPyXL
Key Responsibilities:

Data Extraction:

Input Handling: Loaded a list of URLs from an Excel file (Input.xlsx).
Web Scraping: Used the requests library to fetch HTML content and BeautifulSoup for parsing.
Text Extraction: Extracted only the article titles and main text content, ensuring exclusion of headers, footers, and other non-essential elements.
Data Storage: Saved the extracted text in individual files named by their URL_ID.
Text Analysis:

Tokenization: Utilized NLTK to tokenize text into sentences and words.
Linguistic Metrics: Computed various text metrics including:
Positive and Negative Scores
Polarity and Subjectivity Scores
Average Sentence Length
Percentage of Complex Words
FOG Index
Average Number of Words Per Sentence
Complex Word Count
Word Count
Syllables Per Word
Personal Pronouns Count
Average Word Length
Custom Functions: Developed helper functions to count syllables and identify complex words.
Output Structuring:

Result Compilation: Compiled the analysis results into a structured format as defined by Output Data Structure.xlsx.
File Output: Generated a CSV/Excel file containing all computed variables alongside the original input data.
Outcome:
Successfully extracted and analyzed the text from multiple articles, computed the required linguistic and readability metrics, and saved the results in a well-structured output format. This project enhanced my skills in web scraping, natural language processing, and data analysis using Python.
