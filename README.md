# NLP (Natural Language Processing) 
## What is NLP ? 
  **NLP:**  Natural Language Processing (NLP) is a field of artificial intelligence (AI) that focuses on enabling machines to understand, interpret and generate human language. NLP involves analyzing and processing large amounts of human language data, such as written text or spoken language, and extracting meaning and insights from it.
  
![nlp intro](https://user-images.githubusercontent.com/108387640/235370167-a1108686-e83d-48de-b9a5-dff0df160cfc.png)


## **Application of NLP**
* chatbots
* voice assistants
* sentiment analysis
* language translation
* text summarization and many more 
* With the growing popularity of digital assistants and chatbots, NLP has become an essential tool for businesses to provide efficient and personalized customer service.

![application](https://user-images.githubusercontent.com/108387640/235370203-6c3cb8c3-18e5-443b-b43d-f2111075c8ba.jpg)


## 1) **Regular Expression in NLP**
* Regular expression (regex) is a pattern-matching language used to manipulate and extract text data in NLP. Regular expressions consist of a sequence of characters and metacharacters that represent a particular pattern in a text string.
* For example, regular expressions can be used to extract all email addresses or phone numbers from a text document, or to remove all punctuation marks or stop words from a piece of text.<br>
**Extracting phone Numbers**

![image](https://user-images.githubusercontent.com/108387640/235370494-d71dc92b-e200-4504-8fb0-e4c71b83cc34.png)
as mentioned above in code we are extracting 10 digits, using '\d' we can extract digits and {n} here in place of n you can replace any number that much digits you want .<br>
we are using findall function for matching data with our pattern

**Matching Random Pattern**
![image](https://user-images.githubusercontent.com/108387640/235370776-8d39fa89-d890-4697-9754-0ba5f7de38f8.png)

**Extracting Email Address**

![image](https://user-images.githubusercontent.com/108387640/235371584-c403348a-d2d5-42bd-9d71-bf7c7c29757b.png)


here we are matching text with our designed pattern for mail that is '*[a-z0-9A-z_]*@[a-z0-9A-z_]*\.[a-zA-Z]*' <br> here a-z: means any character between a to z, simillar for A-Z and 0-9.<br>


**you can view my full content of regular expression in my jupyter file** : <br> https://github.com/meet5398/NLP-Natural-Language-Processing-/blob/57611b2b14c58a205c3f93a264daa88f31acc341/regular%20expression%20in%20NLP.ipynb

## 2) **Text Tokenization using spacy and nltk**
**Text Tokenization:** Text tokenization involves breaking text into smaller units or tokens, such as words or sentences. This process enables computers to analyze and understand human language. 
* Tokenization is a crucial step in many natural language processing tasks, including sentiment analysis, named entity recognition, and machine translation.
![image](https://user-images.githubusercontent.com/108387640/236672881-7bfc98b6-163e-4d26-943a-e085fc34492f.png)

### Difference between spacy and nltk
**spacy:** is an open-source software library for advanced natural language processing, written in Python and Cython. It provides a variety of tools for language understanding and processing, including named entity recognition, dependency parsing, and word vectors. **it returns value in terms of object.**<br>

**nltk (Natural Language Toolkit)** is a leading platform for building Python programs to work with human language data. It provides a range of tools for text processing and analysis, including tokenization, stemming, tagging, and parsing. **it returns value in terms of string.**

### Prerequisites
**Before running the code, make sure you have the following installed:**
* Python 3.x
* spacy library (can be installed via pip)
* English language model for spacy (can be downloaded via python -m spacy download en)
* nltk library (can be installed via pip)

### Some imp Screenshots:
![image](https://user-images.githubusercontent.com/108387640/236673197-be8d172b-a3e2-4a4e-a3bc-450d57a5cc7b.png)
 <br>
_in above code we are using spacy and in output we can see that it is returning sentence in **object form**_

![image](https://user-images.githubusercontent.com/108387640/236673289-9a3329ca-6864-4e12-a05d-3900353ecc98.png)<br>
_In above code we are using nltk and we can see that it is returning output of sentence in **string format**_

#### For more details you can view my full jupyter file : https://github.com/meet5398/NLP-Natural-Language-Processing-/blob/d86419c9ceae6953b1696833025c7b4fecfcb6a2/Difference%20between%20Spacy%20and%20Nltk%20.ipynb
