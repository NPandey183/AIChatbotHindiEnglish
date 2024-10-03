This project is a Flask-based chatbot that supports both English and Hindi languages. The chatbot allows users to interact with predefined responses using natural language processing (NLP) techniques such as tokenization, lemmatization, and stopword removal. The conversation can be exported as a PDF with messages in both English and Hindi, using custom fonts like Devanagari for Hindi text.

Features
Multilingual Support: The bot understands and responds in both English and Hindi based on the input.
NLP Preprocessing: Uses tokenization, lemmatization, and stopword removal to process user input.
PDF Export: Export the entire conversation to a PDF file, with proper text formatting and multilingual font support.
Simple UI: A web interface with a basic chat interface that allows for real-time interaction and PDF export.
Tech Stack
Flask: Web framework for Python.
NLTK (Natural Language Toolkit): Used for text preprocessing, including tokenization, lemmatization, and stopwords removal.
ReportLab: For PDF generation, allowing dynamic export of the conversation.
HTML/CSS: Simple frontend for the chatbot UI.
NLP Components
Preprocessing:

Tokenization: Splits the input into words.
Stopword Removal: Removes common words that do not add meaning (e.g., 'the', 'is').
Lemmatization: Converts words to their base form (e.g., "running" → "run").
Keywords: The chatbot uses a keyword-matching technique where it looks for predefined keywords to identify the user's intent and respond accordingly.

PDF Generation
ReportLab: Generates a PDF of the conversation, with multilingual support for English and Hindi. The PDF wraps the text to fit the page and uses the correct font (Devanagari) for Hindi text.
Customization
