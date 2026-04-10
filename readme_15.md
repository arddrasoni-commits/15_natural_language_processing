# Experiment 15  
## Preprocessing Techniques for Text Data and NLP Techniques on Text Data


## Aim
To study the preprocessing techniques and Natural Language Processing (NLP) techniques used for analyzing text data.


## Tools / Software Required
- Python 3.x  
- Google Colab / Jupyter Notebook  

### Python Libraries
- NLTK (Natural Language Toolkit)  
- Pandas  
- NumPy  


## Theory

### 1. Text Data
Text data is a form of unstructured data that includes information in the form of words, sentences, or documents.

**Examples:**
- Emails  
- Social media posts  
- Reviews  
- Articles  
- Messages  

Before applying machine learning or analysis, text data must be cleaned and processed. This process is known as **text preprocessing**.



## 2. Preprocessing Techniques for Text Data

Text preprocessing refers to the process of cleaning and transforming raw text into a format that can be analyzed by computers.

### 1. Text Cleaning
Removes unnecessary elements such as:
- Punctuation  
- Special characters  
- Extra spaces  
- Irrelevant symbols  


### 2. Lowercasing
Converts all text into lowercase so similar words are treated the same.

**Example:**


Data Science → data science



### 3. Tokenization
Splits text into smaller units called tokens (words, sentences, or characters).

**Example:**


Sentence: "Natural language processing is useful"
Tokens: Natural, language, processing, is, useful



### 4. Stop Word Removal
Removes common words that do not add significant meaning.

**Examples:**
- is  
- the  
- and  
- in  
- of  



### 5. Stemming
Reduces words to their root form by removing suffixes.

| Word    | Stem  |
|---------|-------|
| playing | play  |
| running | run   |
| studies | studi |


### 6. Lemmatization
Converts words into their base or dictionary form.

| Word    | Lemma |
|---------|-------|
| running | run   |
| better  | good  |
| studies | study |

More accurate than stemming as it considers grammar and meaning.



## 3. NLP Techniques on Text Data

Natural Language Processing (NLP) enables computers to understand and analyze human language.


### 1. Tokenization
Divides text into words or sentences for easier processing.


### 2. Part-of-Speech (POS) Tagging
Identifies the grammatical category of each word.

**Examples:**
- Noun  
- Verb  
- Adjective  
- Adverb  

**Example:**


Sentence: "Python is powerful"

Python → Noun
is → Verb
powerful → Adjective



### 3. Named Entity Recognition (NER)
Identifies important entities such as:
- Person names  
- Locations  
- Organizations  
- Dates  

**Example:**


Sentence: "Elon Musk founded SpaceX."

Elon Musk → Person
SpaceX → Organization


### 4. Sentiment Analysis
Determines the emotion or opinion in text.

**Types:**
- Positive  
- Negative  
- Neutral  

**Example:**


Review: "This phone is excellent."
Sentiment: Positive




### 5. Text Vectorization
Converts text into numerical format for machine learning.

**Techniques:**
- Bag of Words (BoW)  
- TF-IDF (Term Frequency–Inverse Document Frequency)  


## Applications of NLP
- Chatbots and virtual assistants  
- Machine translation  
- Spam email detection  
- Sentiment analysis  
- Search engines  
- Recommendation systems  


## Conclusion
The preprocessing techniques and NLP techniques used for analyzing text data were studied successfully.
