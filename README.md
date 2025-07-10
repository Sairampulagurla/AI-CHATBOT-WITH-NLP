🤖 NLP Chatbot Project – Overview
🎯 Objective
To create a simple Natural Language Processing (NLP) based rule-based chatbot in Python that responds to user input by matching predefined patterns to known intents.

🧠 Key Features
Intent Recognition using pattern-token matching

Preprocessing with:

Lowercasing

Tokenization (Regex-based)

Stopword removal

Lemmatization (WordNet)

Random Response Generation for variety

Extensible Knowledge Base for adding new intents

Graceful Exit Handling (exit, quit, or bye)

🛠️ Technologies & Libraries Used
Library	Purpose
nltk	Natural Language Toolkit – for lemmatization and stopwords
re	Regular expressions for tokenization
random	Choosing varied responses
input()	Capturing user input in terminal

📋 How It Works
User enters text

The input is preprocessed:

Lowercased

Tokenized via regex

Stopwords removed

Words lemmatized

Tokens are matched against predefined intent patterns

If matched:

A random response is selected from the corresponding intent

If unmatched:

A default fallback response is shown