# NLP Political Manifestos Analysis

This project analyzes political manifestos from the French 1988 legislative elections using Natural Language Processing (NLP) techniques.

---

## Objectives

The main objectives of this project are to:

* explore textual characteristics of political manifestos
* quantify semantic density ("wooden language")
* compare similarity methods (TF-IDF vs embeddings)
* uncover latent structure through clustering

---

## Dataset

The analysis is based on the **Archelec corpus**, which contains political manifestos from the 1988 French legislative elections.

The dataset includes several thousand documents written by candidates from different political parties and regions, providing a diverse representation of political discourse.

The texts were digitized using Optical Character Recognition (OCR), which introduces noise such as:

* spelling errors
* inconsistent formatting
* missing or corrupted characters

Despite these limitations, the dataset offers a valuable and realistic representation of political communication.

For this project, we focus exclusively on the 1988 legislative elections to ensure consistency in the analysis.

---

## Repository Structure

```
.
├── 1_data_exploration.ipynb
├── 2_semantic_density.ipynb
├── 3a_similarity_analysis.ipynb
├── 3b_similarity_analysis.pdf
├── 4_advanced_analysis.ipynb
├── 4_advanced_analysis.pdf
├── report_notebook.pdf
├── requirements.txt
└── README.md
```

---

## Notebooks

### 1. Data Exploration

* dataset overview
* text statistics
* document length distribution

### 2. Semantic Density

* definition of semantic density
* analysis of informational content
* identification of "wooden language" patterns

### 3. Similarity Analysis

* TF-IDF vs embedding-based similarity
* document ranking task
* qualitative comparison of retrieved texts
* PCA visualization
* similarity score distribution

### 4. Advanced Analysis

* clustering using K-Means
* PCA-based visualization of clusters
* qualitative cluster interpretation
* intra-cluster similarity analysis

---

## Important Note

Due to GitHub rendering limitations, notebooks 3 and 4 may not display correctly in preview.

👉 Please refer to the **PDF versions** for a complete and clean view of the results.

The original notebooks are still provided and can be downloaded and executed locally or in Google Colab.

---

## Requirements

Install the required libraries with:

```
pip install -r requirements.txt
```

---

## Project Summary

This project combines quantitative and qualitative approaches to analyze political discourse.

The results show that:

* embedding-based methods capture deeper semantic relationships than TF-IDF
* political manifestos exhibit structured patterns in semantic space
* clustering reveals meaningful groupings in rhetorical and thematic content

---

## Author

Gabriele Tersigni
ENSAE Paris

