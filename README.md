# 🧠 NLP Unit 1 — Practical Programs

> A hands-on collection of **Natural Language Processing (NLP)** programs implemented using **Python, NLTK, and spaCy**.

This repository contains **6 practical programs** covering fundamental NLP concepts, from basic text preprocessing to **Named Entity Recognition (NER)**.

---

## 🚀 What's Inside?

| #  | Practical                       | Main Concepts                     | Library     |
| -- | ------------------------------- | --------------------------------- | ----------- |
| 01 | 🔤 **Tokenization**             | Sentence & Word Tokenization      | NLTK, spaCy |
| 02 | 🌱 **Stemming & Lemmatization** | Root & Base Word Extraction       | NLTK        |
| 03 | 🛑 **Stop-word Removal**        | Tokenization & Filtering          | NLTK        |
| 04 | 🏷️ **POS Tagging**             | Grammatical Classification        | NLTK        |
| 05 | 🌳 **Parsing & Chunking**       | Syntax & Dependency Analysis      | NLTK, spaCy |
| 06 | 📍 **Named Entity Recognition** | Entity Detection & Classification | spaCy       |

---

# 📚 Practicals

## 01 — 🔤 Tokenization

**Folder:** `01_Tokenization`

Tokenization is the process of breaking text into smaller units called **tokens**, such as sentences and words.

### Concepts

* Sentence Tokenization
* Word Tokenization

### Tools

* Python
* NLTK
* spaCy

📄 **File:** `tokenization.ipynb`

---

## 02 — 🌱 Stemming & Lemmatization

**Folder:** `02_Stemming_Lemmatization`

This practical demonstrates techniques used to obtain the **root or base form of words**.

### Stemming

Stemming removes word endings to obtain a root form. The result may sometimes not be a valid dictionary word.

**Example:**

```text
Studies → Studi
Playing → Play
```

### Lemmatization

Lemmatization converts a word into its meaningful **dictionary base form**.

**Example:**

```text
Studies → Study
Playing → Play
```

### Concepts

* Porter Stemming
* WordNet Lemmatization

### Tools

* Python
* NLTK Porter Stemmer
* NLTK WordNet Lemmatizer

📄 **File:** `stemming_lemmatization.ipynb`

---

## 03 — 🛑 Stop-word Removal

**Folder:** `03_Stopword_Removal`

Stop words are frequently occurring words that may provide limited information for certain NLP tasks.

### Examples

```text
the
is
a
an
and
of
```

This practical demonstrates how stop words can be identified and removed from a document using NLTK.

### Concepts

* Word Tokenization
* Stop-word Identification
* Stop-word Removal

### Tools

* Python
* NLTK

📄 **File:** `stopword_removal.ipynb`

---

## 04 — 🏷️ Part-of-Speech Tagging

**Folder:** `04_POS_Tagging`

**POS Tagging** assigns a grammatical category to every word in a sentence.

### Common POS Categories

* Noun
* Verb
* Adjective
* Adverb
* Preposition
* Determiner

### Concepts

* Word Tokenization
* POS Tagging
* Grammatical Categories

### Tools

* Python
* NLTK

📄 **File:** `pos_tagging.ipynb`

---

## 05 — 🌳 Parsing & Chunking

**Folder:** `05_Parsing_Chunking`

This practical demonstrates **syntactic analysis** using regular-expression-based chunking and dependency parsing.

### Concepts

* POS Tagging
* Regular Expression Chunking
* Noun Phrase Chunking
* Dependency Parsing
* Grammatical Relationships

### Tools

* Python
* NLTK
* spaCy

📄 **File:** `parsing_chunking.ipynb`

---

## 06 — 📍 Named Entity Recognition

**Folder:** `06_Named_Entity_Recognition`

**Named Entity Recognition (NER)** identifies and classifies important entities present in text.

### Entity Examples

| Entity          | Example           |
| --------------- | ----------------- |
| 👤 Person       | Narendra Modi     |
| 🏢 Organization | Google            |
| 📍 Location     | India             |
| 📅 Date         | 15 September 2026 |
| 💰 Money        | ₹10,000           |
| 🌎 GPE          | Delhi             |

### Concepts

* Named Entity Recognition
* Entity Classification
* Entity Labels

### Tools

* Python
* spaCy

📄 **File:** `ner.ipynb`

---

# 🛠️ Technologies Used

<p align="center">

<img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/NLTK-NLP-154f5c?style=for-the-badge"/>
<img src="https://img.shields.io/badge/spaCy-NLP-09A3D5?style=for-the-badge"/>

</p>

* 🐍 Python 3
* 🔤 NLTK
* 🧠 spaCy
* 💬 Natural Language Processing

---

# ⚙️ Installation

Make sure **Python 3** is installed on your system.

### Install Required Libraries

```bash
pip install nltk spacy
```

### Install spaCy English Model

```bash
python -m spacy download en_core_web_sm
```

### NLTK Resources

The required NLTK resources are downloaded by the respective programs when needed.

These include:

```text
punkt
punkt_tab
stopwords
averaged_perceptron_tagger_eng
wordnet
omw-1.4
```

---

# ▶️ How to Run

The programs are provided as Python `.ipynb` files.

You can open and run them using any environment that supports Python notebooks, such as:

* Jupyter Notebook
* JupyterLab
* VS Code with the Jupyter extension

Open the required file and execute the cells sequentially.

---

# 📂 Repository Structure

```text
NLP-Unit-1-Programs/
│
├── 📁 01_Tokenization/
│   └── 📄 tokenization.ipynb
│
├── 📁 02_Stemming_Lemmatization/
│   └── 📄 stemming_lemmatization.ipynb
│
├── 📁 03_Stopword_Removal/
│   └── 📄 stopword_removal.ipynb
│
├── 📁 04_POS_Tagging/
│   └── 📄 pos_tagging.ipynb
│
├── 📁 05_Parsing_Chunking/
│   └── 📄 parsing_chunking.ipynb
│
├── 📁 06_Named_Entity_Recognition/
│   └── 📄 ner.ipynb
│
└── 📄 README.md
```

---

# 🎯 Learning Objectives

Through these practicals, the following fundamental NLP concepts are demonstrated:

* Sentence Tokenization
* Word Tokenization
* Stemming
* Lemmatization
* Stop-word Removal
* Part-of-Speech (POS) Tagging
* Parsing
* Chunking
* Named Entity Recognition (NER)

The programs demonstrate how **raw text can be processed, transformed, and analyzed** using different NLP techniques.

---

# 🎓 Course Outcome

This repository provides hands-on understanding of fundamental **Natural Language Processing** techniques and their implementation using popular Python NLP libraries.

The practicals demonstrate a basic NLP workflow:

```text
Raw Text
   ↓
Tokenization
   ↓
Text Preprocessing
   ↓
Stemming / Lemmatization
   ↓
POS Tagging
   ↓
Parsing & Chunking
   ↓
Named Entity Recognition
   ↓
Processed & Analyzed Text
```

---

# 👨‍💻 Author

### Aditya Patel

**B.Tech CSE (AI) | NLP Practical Work**

🔗 **GitHub:**
https://github.com/adityapatel0812

---

# 📌 Purpose

This repository is created for **academic and practical learning purposes** and demonstrates fundamental NLP concepts using:

**Python + NLTK + spaCy**

---

<p align="center">
  ⭐ If you find this repository useful, consider giving it a star!
</p>
