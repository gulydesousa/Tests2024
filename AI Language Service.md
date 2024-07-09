## Azure AI Language Service
Includes features for understanding and analyzing text.

## Features

| Feature                                | Description                                                                                              |
|----------------------------------------|----------------------------------------------------------------------------------------------------------|
| **Sentiment Analysis**                 | Opinion mining to categorize text as positive, neutral, or negative. Prebuilt machine learning classification model to evaluate text. Categories: positive, neutral, negative. Positive score: 0.90, Neutral score: 0.10, Negative score: 0.00 |
| **Text Analysis**                      | Identifies key terms or named entities in text.                                                          |
| **Named Entity Recognition (NER)**     | Identifies people, places, events, and more. Can be customized to extract custom categories.             |
| **Entity Linking**                     | Identifies known entities together with a link to Wikipedia.                                             |
| **Personal Identifying Information (PII)** | Identifies personally sensitive information.                                                            |
| **Key Phrase Extraction**              | Lists the main concepts from unstructured text.                                                          |
| **Text Summarization**                 | Summarizes main points of a large body of text.                                                          |
| **Machine Translation**                | Automatically translates text from one language to another.                                              |
| **Language Detection**                 | Identifies the language of the text and returns a language code. <br> - Language name: <span style="color:#D64B91">_UNKNOWN_</span> <br>- ISO 639-1 language code <span style="color:#D64B91">_UNKNOWN_</span> <br>- Confidence level: <span style="color:#D64B91">_NaN_</span> |
| **Conversational Language Understanding** | Solutions such as bots or digital assistants to interpret natural language input and return appropriate responses. |

## Text Processing

| Feature            | Description                                                                                   |
|--------------------|-----------------------------------------------------------------------------------------------|
| **Tokenization**   | Generates tokens for partial words or combinations of words and punctuation.                  |
| **Text Normalization** | Removing punctuation and changing all words to lower case.                               |
| **Stop Word Removal**  | Removes common words that are usually not useful for understanding the main content.      |
| **N-grams**        | Multi-term phrases such as "I have" or "he walked".                                           |
| **Stemming**       | Consolidates words before counting them, so that words with the same root are treated as the same word. |

## Analysis

| Feature                                    | Description                                                                                                   |
|--------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| **Frequency Analysis**                     | Counts the number of occurrences of each token.                                                               |
| **Term Frequency - Inverse Document Frequency (TF-IDF)** | Measures how often a word or term appears in one document compared to its frequency across the entire collection of documents. |
| **Classification Algorithm**               | Classifies text as positive or negative to perform sentiment analysis or opinion mining.                      |
| **Embeddings**                             | Encoding of language tokens as vectors.                                                                       |
