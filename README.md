# nlp1

A collection of **Natural Language Processing (NLP)** Jupyter Notebooks demonstrating key concepts and workflows using Python libraries such as NLTK, spaCy, scikit-learn, and Gensim. Each notebook focuses on practical implementation of a major NLP technique, from basic preprocessing to story generation and topic modeling.

## Repository Contents

- **ai_story_generator.ipynb**  
  *AI-based Story Generator using GPT-2 with a Gradio interface.*  
  This notebook lets you generate genre-specific stories interactively using OpenAI's GPT-2 model. It provides a simple UI via Gradio for dynamic story generation.

- **cadl1.ipynb**  
  *Text Preprocessing with NLTK and SpaCy.*  
  Covers all core preprocessing steps:  
  - Tokenization  
  - Stop word removal  
  - Stemming  
  - Lemmatization  
  It uses NLTK for most steps and spaCy for advanced lemmatization.

- **cadl2.ipynb**  
  *Text Feature Extraction using BoW and TF-IDF.*  
  Demonstrates how to convert a corpus into numerical features using:  
  - Bag-of-Words (BoW) vectorization  
  - TF-IDF (Term Frequency-Inverse Document Frequency)  
  Both are essential for feeding text into ML models.

- **cadl3.ipynb**  
  *Named Entity Recognition (NER) with SpaCy.*  
  Extracts and visualizes entities like people and organizations from sample texts using spaCy's `en_core_web_sm` model. Also demonstrates how to store structured results in a CSV.

- **cadl4.ipynb**  
  *Topic Modeling with Latent Dirichlet Allocation (LDA).*  
  Applies Gensim's LDA to discover abstract "topics" in a corpus and visualizes them with pyLDAvis.

## How to Use

1. **Clone or Download the Repository.**
2. Open notebooks in Jupyter or Colab.
3. Install required dependencies for each notebook (listed at the top, e.g., `nltk`, `spacy`, `scikit-learn`, `gensim`, `pyLDAvis`).
4. Run the cells and experiment with the provided samples or your own text data.

## Learning Objectives

- Understand and implement the NLP preprocessing pipeline.
- Convert text to numerical representations for machine learning.
- Recognize and extract entities from raw text.
- Build a basic AI story generator.
- Apply topic modeling to textual data.

---

This README reflects the latest structure and purpose of each file in your repository. You can copy this directly into your `README.md` for a polished, informative repo landing page.
