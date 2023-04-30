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


## **Regular Expression in NLP**
* Regular expression (regex) is a pattern-matching language used to manipulate and extract text data in NLP. Regular expressions consist of a sequence of characters and metacharacters that represent a particular pattern in a text string.
* For example, regular expressions can be used to extract all email addresses or phone numbers from a text document, or to remove all punctuation marks or stop words from a piece of text
**Extracting phone Numbers**

![image](https://user-images.githubusercontent.com/108387640/235370494-d71dc92b-e200-4504-8fb0-e4c71b83cc34.png)
as mentioned above in code we are extracting 10 digits, using '\d' we can extract digits and {n} here in place of n you can replace any number that much digits you want .<br>
we are using findall function for matching data with our pattern

**Matching Random Pattern**
![image](https://user-images.githubusercontent.com/108387640/235370776-8d39fa89-d890-4697-9754-0ba5f7de38f8.png)

**Extracting Email Address**

![image](https://user-images.githubusercontent.com/108387640/235371584-c403348a-d2d5-42bd-9d71-bf7c7c29757b.png)


here we are matching text with our designed pattern for mail that is '*[a-z0-9A-z_]*@[a-z0-9A-z_]*\.[a-zA-Z]*' <br> here a-z: means any character between a to z, simillar for A-Z and 0-9.<br>


** you can view my full content of regular expression in my jupyter file : <br> https://github.com/meet5398/NLP-Natural-Language-Processing-/blob/57611b2b14c58a205c3f93a264daa88f31acc341/regular%20expression%20in%20NLP.ipynb
