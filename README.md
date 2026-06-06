# COVID-19 Research Articles — Clustering & Topic Modeling

Groups COVID-19 research articles by theme using **clustering** and **topic modeling
(LDA and NMF)** after text preprocessing (lemmatization) and dimensionality reduction.

## Why This Project Matters

The volume of COVID-19 literature made manual review impractical. Unsupervised NLP — clustering
plus topic modeling — surfaces the dominant themes across a large article corpus without labeled
data, making the literature easier to navigate.

## Tech Stack

- **Language:** Python (Jupyter Notebook)
- **Methods:** Text preprocessing (lemmatization), dimensionality reduction, clustering, topic modeling with LDA and NMF
- **Libraries:** scikit-learn (LDA, NMF), plus NLP preprocessing tooling *(confirm exact imports in the notebook)*

## Key Features

- Lemmatization and cleaning of raw article text.
- Dimensionality reduction prior to modeling.
- Clustering of articles into thematic groups.
- Topic modeling with both **LDA** and **NMF** for comparison.

## Repository Structure

```text
COVID-19-Research-Articles-Clustering-and-Topic-Modeling-/
└── Project.ipynb   # preprocessing, clustering, LDA/NMF topic modeling
```

## How to Run

```bash
pip install scikit-learn pandas numpy matplotlib jupyter   # confirm against notebook imports
jupyter notebook Project.ipynb
```

## Example Output / Results

To be added after verification. *(Add the discovered topics / top terms per topic, number of
clusters, and any comparison between LDA and NMF once confirmed from the notebook.)*

## What I Learned

- Applying unsupervised NLP (clustering + topic modeling) to a real corpus.
- Comparing LDA and NMF as topic-modeling approaches.
- Text preprocessing and dimensionality reduction for document data.

## Future Improvements

- Add example topics and a short results summary once verified.
- Add a `requirements.txt` and a data/source note.

## Limitations

- Coursework/portfolio project; results still to be surfaced here from the notebook.
