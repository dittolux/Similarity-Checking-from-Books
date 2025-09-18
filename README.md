# Similarity-Checking-from-Books

This project is a command-line text analysis tool built in C++ that determines the lexical similarity between different literary works. The program processes a collection of over 60 classic texts, performing a series of analytical steps:

Parsing & Cleaning: It reads each text file, converts all words to lowercase, removes punctuation, and filters out common "stop words" to ensure the analysis is based on meaningful vocabulary.

Frequency Analysis: The engine calculates the frequency of each word within a book and normalizes these scores to understand the statistical importance of each term.

Feature Extraction: It identifies the top 100 most frequently used words for each book, creating a unique lexical "fingerprint."

Similarity Scoring: By comparing these fingerprints, the program calculates a similarity index between every pair of books, quantifying how much their core vocabularies overlap.

Finally, the tool outputs detailed reports, including a complete similarity matrix and a ranked list of the top 10 most similar book pairs. The project demonstrates efficient C++ programming practices, including file I/O, data manipulation with STL containers (map, list, vector), and algorithmic logic.
