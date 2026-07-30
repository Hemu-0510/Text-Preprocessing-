📝 Text Preprocessing Using Python
## Project Overview

This project demonstrates the process of cleaning and preprocessing raw text data using Python. The dataset contains conversations with URLs, email addresses, emojis, HTML tags, hashtags, mentions, phone numbers, punctuation, and special characters. The preprocessing pipeline converts the raw text into a clean format suitable for Natural Language Processing (NLP) tasks.
.

## Objectives
Read raw text data from a CSV file.
Clean noisy text using regular expressions.
Convert text to lowercase.
Remove URLs, emails, phone numbers, HTML tags, emojis, hashtags, and special characters.
Remove punctuation and numbers.
Remove extra white spaces.
Save the cleaned text into a new CSV file.

## Technologies Used
Python 3
Pandas
NLTK
Regular Expressions (re)
JupyterLab
## Project Structure
Text-Preprocessing/
│── raw_text.csv
│── cleaned_text.csv
│── Text_Preprocessing.ipynb
│── README.md
## Dataset Description

The dataset consists of 15 sample conversations containing:

URLs
Email addresses
Phone numbers
HTML tags
Emojis
Hashtags
User mentions
Punctuation
Numbers
Mixed uppercase and lowercase text
## Text Preprocessing Pipeline
Raw Text
     │
     ▼
Convert to Lowercase
     │
     ▼
Remove URLs
     │
     ▼
Remove Email Addresses
     │
     ▼
Remove Phone Numbers
     │
     ▼
Remove HTML Tags
     │
     ▼
Remove Mentions (@)
     │
     ▼
Remove Hashtags (#)
     │
     ▼
Remove Emojis
     │
     ▼
Remove Punctuation & Numbers
     │
     ▼
Remove Extra Spaces
     │
     ▼
Clean Text
## Processing Techniques
✔ Lowercase Conversion

Converts all text into lowercase to maintain consistency.

✔ URL Removal

Removes website links from the text.

Example:

https://www.technews.com/latest
✔ Email Removal

Removes email addresses.

Example:

arunkumar123@gmail.com
✔ Phone Number Removal

Removes mobile numbers from the dataset.

Example:

9123456780
✔ Emoji Removal

Removes emojis and other non-ASCII characters.

Example:

😊🎉🔥📧
✔ Number Removal

Removes digits and numeric values.

Example:

65000
205
92
## Before vs After Comparison
Original Text	Cleaned Text
Good morning everyone!! 👋 Have a wonderful day! 😊	good morning everyone have a wonderful day
Check this article: https://www.technews.com/latest 🚀	check this article
Contact me at arunkumar123@gmail.com 📧	contact me at for more information
Happy Birthday, Priya!!! 🎂🎉	happy birthday priya have an amazing year ahead
## Features
Reads CSV dataset
Cleans noisy text
Uses Regular Expressions
Converts text to lowercase
Removes URLs
Removes email addresses
Removes phone numbers
Removes HTML tags
Removes emojis
Removes hashtags
Removes mentions
Removes punctuation
Removes numbers
Removes extra spaces
Generates a cleaned CSV file
## Conclusion

This project demonstrates a complete text preprocessing workflow using Python, Pandas, NLTK, and Regular Expressions. It transforms raw text into a clean and structured format by removing unwanted elements such as URLs, emails, phone numbers, HTML tags, emojis, punctuation, and extra spaces. The resulting cleaned dataset is suitable for downstream NLP and machine learning applications, providing a solid foundation for text analysis and model development.
