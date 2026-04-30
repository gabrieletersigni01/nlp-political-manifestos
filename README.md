# NLP Analysis of Political Manifestos

This project analyzes political manifestos from the 1988 French legislative elections using Natural Language Processing (NLP) techniques.

---

## Objectives

The main objectives of this project are to:

- explore the textual characteristics of political manifestos  
- quantify semantic density as a proxy for "wooden language"  
- compare lexical and semantic similarity methods (TF-IDF vs embeddings)  
- uncover latent structure in the corpus through clustering  

---

## Dataset

The analysis is based on the **Archelec corpus**, which contains political manifestos from the 1988 French legislative elections.

The dataset includes several thousand documents written by candidates from different political parties and regions, providing a diverse representation of political discourse.

The texts were digitized using Optical Character Recognition (OCR), which introduces noise such as:
- spelling errors  
- inconsistent formatting  
- missing or corrupted characters  

This noise is an important aspect of the dataset, as it reflects real-world conditions of historical textual data.

⚠️ **The dataset is not included in this repository** due to its size and format.

To run the notebooks:
- download the dataset separately  
- upload it manually when prompted (e.g., in Google Colab)

All notebooks are designed to work with manual dataset upload.

---
## Repository Structure

```
.
├── 1_data_exploration.ipynb
├── 1_data_exploration.ipynb-pdf
├── 2_semantic_density.ipynb
├── 2_semantic_density.ipynb-pdf
├── 3a_similarity_analysis.ipynb
├── 3b_similarity_analysis-pdf
├── 4_advanced_analysis.ipynb
├── 4_advanced_analysis-pdf
├── report_notebook.pdf
├── requirements.txt
└── README.md
---

## Notebooks

### 1. Data Exploration
- dataset overview  
- text statistics  
- document length distribution  

### 2. Semantic Density
- definition of semantic density  
- analysis of informational content  
- identification of "wooden language" patterns  

### 3. Similarity Analysis
- TF-IDF vs embedding-based similarity  
- document ranking task  
- qualitative comparison of retrieved texts  
- similarity score distribution  

### 4. Advanced Analysis
- clustering using K-Means  
- PCA-based visualization  
- qualitative cluster interpretation  
- intra-cluster similarity analysis  

---

## Notebooks and PDFs

All notebooks are fully viewable directly on GitHub.

PDF versions are also provided for:
- easier reading  
- quick review of results  
- consistent formatting when sharing or submitting  

---

## Requirements

Install the required libraries with:
pip install -r requirements.txt

---

## Project Summary

This project combines quantitative and qualitative approaches to analyze political discourse.

The results show that:
- embedding-based methods capture deeper semantic relationships than TF-IDF  
- political manifestos exhibit structured patterns in semantic space  
- clustering reveals meaningful groupings in rhetorical style and thematic content  

---

## Author

Gabriele Tersigni  
ENSAE Paris  
Machine Learning for NLP


