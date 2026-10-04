# 📝 Text Summarization

A Natural Language Processing mini-project that automatically generates a concise summary from a longer text.

## 🎯 Objective

To develop an extractive text summarization system that identifies important sentences from a document and creates a shorter summary while preserving the main information.

## 🧠 Method

**Extractive Text Summarization**

The system:

1. Tokenizes the text into sentences and words.
2. Removes common stop words.
3. Calculates word frequencies.
4. Scores sentences based on important words.
5. Selects the highest-scoring sentences.
6. Generates the final summary.

## 🛠️ Technologies

- Python
- NLTK
- Pandas
- Gradio
- Google Colab

## ⚙️ System Architecture

```text
                 Long Text
                     │
                     ▼
            Sentence Tokenization
                     │
                     ▼
              Word Tokenization
                     │
                     ▼
              Remove Stopwords
                     │
                     ▼
           Word Frequency Analysis
                     │
                     ▼
             Sentence Scoring
                     │
                     ▼
          Important Sentences
                     │
                     ▼
              Final Summary
