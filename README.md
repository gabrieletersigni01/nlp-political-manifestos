# NLP Analysis of Political Manifestos

This project investigates the semantic similarity of political manifestos using Natural Language Processing (NLP) techniques.

The objective is to represent documents as dense vector embeddings and analyze how political texts relate to each other in semantic space. By doing so, we aim to explore whether ideological proximity can be captured directly from textual data.

---

## Dataset

The dataset is derived from the Archelec corpus, which contains political manifestos from French elections.

This project focuses exclusively on a subset of the data corresponding to the **French legislative elections of 1988**.

Due to size constraints, the dataset is **not included** in this repository. To run the notebook, the user must manually upload the dataset before execution.

---

## Methodology

The analysis follows a standard NLP pipeline:

### 1. Text preprocessing
- Lowercasing
- Removal of punctuation
- Basic cleaning of raw OCR text

### 2. Document representation
Each manifesto is transformed into a dense vector using a pretrained transformer-based model (e.g. BERT or Sentence-Transformers).

These embeddings capture semantic information beyond simple word matching.

### 3. Similarity computation
We compute **cosine similarity** between document embeddings to measure how close two manifestos are in semantic space.

### 4. Ranking
For a given document, we retrieve the most similar manifestos based on similarity scores.

### 5. Visualization
We use:
- **Similarity heatmaps** to observe global relationships
- **t-SNE projections** to visualize clustering patterns in two dimensions

---

## Results

The analysis highlights several interesting patterns:

- Documents with similar political orientations tend to have higher similarity scores
- Embeddings capture relationships that are not visible through simple lexical overlap
- Visualizations suggest the presence of latent clusters in the data

These results indicate that semantic representations can effectively reflect ideological proximity between political texts.

---

## Limitations

This project has several limitations:

- The dataset is restricted to a single election year (1988), which limits generalizability
- No fine-tuning of the embedding model was performed
- OCR noise in the source data may affect text quality
- The analysis is exploratory and does not include formal evaluation metrics

---

## How to run

1. Install the required libraries:

pip install -r requirements.txt

2. Open the notebook:

nlp_political_manifestos.ipynb

3. Upload the dataset when prompted and run all cells

## Notes

- The dataset is not included in this repository
- The notebook is designed to run on Google Colab
- Results may vary depending on the dataset used

## Notebook Preview

A PDF version of the notebook is available in this repository.

## Author

Gabriele Tersigni  
ENSAE Paris
