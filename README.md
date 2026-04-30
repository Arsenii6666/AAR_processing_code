# AAR Processing Code

## Overview

This repository contains code for processing and analyzing **After Action Reports (AARs)** using Natural Language Processing (NLP) techniques. The project focuses on extracting structured information from historical military documents and preparing it for further analysis.

The pipeline includes:

* Data preprocessing and cleaning
* Named Entity Recognition (NER)
* Model training and evaluation
* Structured output generation

---

## Project Structure

```
.
├── README.md
├── обробка даних.ipynb          # Data preprocessing and cleaning
├── spacy навчання і використання.ipynb   # spaCy model training and usage
```

---

## Data

The dataset used in this project is available here:

👉 [https://drive.google.com/drive/folders/1Q9LxGnhdl15CaJfnEoTwNuMrspyegdyo?usp=sharing](https://drive.google.com/drive/folders/1Q9LxGnhdl15CaJfnEoTwNuMrspyegdyo?usp=sharing)

The data consists of historical After Action Reports that require cleaning and normalization before applying NLP techniques.

---

## Workflow

### 1. Data Preprocessing

Notebook: `обробка даних.ipynb`

This step includes:

* Loading raw AAR data
* Cleaning text (removing noise, formatting issues)
* Normalizing inconsistent entries
* Preparing datasets for annotation and training

---

### 2. Model Training and Usage

Notebook: `spacy навчання і використання.ipynb`

This notebook covers:

* Creating and annotating training data
* Training a custom spaCy NER model
* Evaluating model performance
* Applying the model to extract entities from AAR texts

---

## Technologies Used

* Python
* spaCy
* pandas
* Jupyter Notebook

---

## How to Run

1. Clone the repository:

```
git clone https://github.com/Arsenii6666/AAR_processing_code.git
cd AAR_processing_code
```

2. Install dependencies:

```
pip install -r requirements.txt
```

*(If requirements.txt is not provided, install manually: spaCy, pandas, etc.)*

3. Download the dataset from the provided Google Drive link.

4. Open notebooks in Jupyter or VS Code and run them step by step:

* Start with `обробка даних.ipynb`
* Then run `spacy навчання і використання.ipynb`

---

## Results

The output of the pipeline is:

* Cleaned and structured AAR data
* Extracted entities (e.g., locations, units, dates, events)
* Tables ready for further analysis or visualization

---

## Use Cases

* Historical document analysis
* Military history research
* Information extraction from unstructured text
* NLP experimentation on domain-specific corpora

---

## Future Improvements

* Improve NER accuracy with larger annotated datasets
* Add relation extraction between entities
* Automate evaluation metrics
* Deploy as a web service or API

---

## Author

Arsenii Kazymyr

---
