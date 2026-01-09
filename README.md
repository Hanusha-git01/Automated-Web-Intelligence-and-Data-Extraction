Automated Web Intelligence & Data Extraction Pipeline-
Project Overview-
This project is an automated Python-based data engineering solution designed to extract unstructured text from web sources and transform it into structured, CRM-ready datasets. It specializes in large-scale data harvesting and high-level Natural Language Processing (NLP) for business intelligence.

Core Features-
Scalable Web Scraping: Uses BeautifulSoup and Requests to programmatically extract titles and article content.

NLP Analysis Engine: Calculates 13 key text metrics, including:

Readability: Fog Index, Average Sentence Length, and Complex Word Count.

Sentiment Analysis: Positive/Negative scores, Polarity, and Subjectivity.

Complexity: Syllables per word and average word length.

Compliance-Focused: Engineered with privacy awareness (GDPR/APPI) by focusing on public business data and utilizing custom headers to respect server protocols.

Technical Stack-
Language: Python 3.x

Libraries: Pandas, NLTK, BeautifulSoup4, Requests

Setup & Usage-
Install dependencies: pip install pandas requests beautifulsoup4 nltk openpyxl

Input: Place your target URLs in an Excel file named Input.xlsx.

Run: Execute the script to generate:

extracted_articles/: Individual text files for each source.

Output_Data_Structure.xlsx: A comprehensive spreadsheet with all 13 analysis variables.
