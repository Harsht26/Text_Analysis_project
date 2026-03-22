# Text_Analysis_project
This project automates the extraction of textual data from web articles using BeautifulSoup and performs advanced Natural Language Processing (NLP). It calculates 13 key variables including Polarity, Subjectivity, Fog Index, and Syllable counts, delivering insights into sentiment and readability in a structured Excel format
Data Extraction and NLP Text Analysis

📌 Project Objective
The goal of this project is to extract textual content from various URLs and perform advanced Natural Language Processing (NLP) to compute 13 specific metrics. These metrics include sentiment scores (Positive/Negative), readability indices (Fog Index), and statistical data (Word Count, Syllable Count, etc.).

🛠️ Tech Stack
Language: Python
Libraries: - BeautifulSoup4 or Selenium (for Web Scraping)
Pandas (for Data Manipulation)
NLTK (for Text Processing & Stopwords)
Re (Regex for Personal Pronouns)

🚀 Features
1. Data Extraction
Reads URLs from an Input.xlsx file.
Extracts only the Article Title and Article Text.
Automatically excludes headers, footers, and sidebars.
Saves each article as a .txt file named after its URL_ID.

2. Textual Analysis (NLP)
Based on the Text Analysis.docx methodology, the following variables are calculated:
Sentimental Analysis: Positive Score, Negative Score, Polarity Score, and Subjectivity Score.
Readability: Average Sentence Length, Percentage of Complex Words, and Gunning Fog Index.
Statistics: Complex Word Count, Total Word Count (cleaned), Syllables per word, Personal Pronouns (I, we, my, ours, us), and Average Word Length.

📂 Project Structure
Plaintext
├── main_script.py            # Core Python logic
├── Input.xlsx                # List of URLs to scrape
├── StopWords/                # Folder containing stopword lists
├── MasterDictionary/         # Folder with positive/negative words
├── extracted_articles/       # Folder where .txt files are saved
├── Output_Data_Structure.xlsx # Final formatted result
└── README.md                 # Project documentation
