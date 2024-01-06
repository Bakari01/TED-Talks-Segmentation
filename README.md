# TED Talks Segmentation and Topics Extraction using Machine Learning

## Project Overview

This project involves segmenting TED Talks into clusters and performing topic modeling on each cluster. The goal is to identify the main themes or topics in each cluster of TED Talks. The project is implemented in a Jupyter notebook.

## Dependencies

- Python
- Jupyter
- NLTK
- Gensim
- PyLDAvis
- Seaborn
- Matplotlib

## Files in this Repository

- `TED_Talks_Segmentation_and_Topics_Extraction.ipynb`: This is the Jupyter notebook where the TED Talks are segmented and topic modeling is performed.

## How to Run the Project

1. Clone this repository.
2. Install the dependencies.
3. Open the `TED_Talks_Segmentation_and_Topics_Extraction.ipynb` notebook in Jupyter.
4. Run all cells in the notebook.

## Project Details

The project follows these main steps:

1. Preprocessing: The TED Talks are tokenized, filtered to remove non-alphabetic tokens, and stemmed.
2. Clustering: The preprocessed TED Talks are segmented into clusters.
3. Topic Modeling: Topic modeling is performed on each cluster using the LDA (Latent Dirichlet Allocation) model.
4. Visualization: The topics identified by the LDA model are visualized using PyLDAvis.

## Results

The results of the topic modeling are displayed as an interactive visualization in the Jupyter notebook. Each bubble on the plot represents a topic, and the size of the bubble indicates the prevalence of that topic in the TED Talks.

## Future Work

Future work could involve refining the preprocessing steps, experimenting with different clustering algorithms, or trying different parameters for the LDA model.