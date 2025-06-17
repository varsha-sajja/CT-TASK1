# CT-TASK1
Company: CODTECH IT SOLUTIONS PVT.LTD

Name: Sajja Varsha

Intern ID: CT06DL1341

Domain: Artificial Intelligence

Batch Duration: may 5th, 2025 to june 20th, 2025

Mentor Name: Neela Santhosh Kumar

# Description
This Python script provides a tool for summarizing lengthy articles using Natural Language Processing (NLP) techniques. It leverages the sumy library to extract concise summaries from input text.

# Features
Summarization Methods: Supports three popular summarization algorithms: LSA (Latent Semantic Analysis): Suitable for long, well-structured documents where thematic understanding is crucial. Luhn: Efficient for quickly summarising short to moderately sized documents. TextRank: A robust choice for most tasks, offering nuanced and context-aware summaries. Customizable Summary Length: Adjust the number of sentences in the summary using the sentence_count parameter. Easy to Use: input the text and select the desired summarization method.

# Requirements
Python 3.x sumy library nltk library spacy library

# Installation
Install the required libraries using pip: bash pip install sumy nltk spacy Download NLTK resources: python import nltk nltk.download('punkt') nltk.download('punkt_tab') nltk.download('stopwords')

# Usage
Run the script. Enter the text you want to summarize when prompted. The script will generate a concise summary and display it.

# Example
Enter the text you want to summarize: [Your input text here] Original Text: [Your input text here] Summary: [Generated summary]

# Note
The script uses LSA as the default summarization method. You can change this by modifying the method parameter in the summarize_text function. For optimal results, ensure that the input text is well-structured and grammatically correct.


# Output
![Image](https://github.com/user-attachments/assets/78782aa3-a233-437e-8ce6-d8676d27aa42)
