# Natural Language Processing and Text Analytics - Final Exam

#### May 30, 2025

Final Exam for _Natural Language Processing and Text Analytics (CDSCO1002E)_ Spring 2025 at Copenhagen Business School

### Students:

Caoimhe Gallahue _(175890)_: [@caoimhegall](https://www.github.com/caoimhegall), caga24ad@student.cbs.dk

Eirik Sundsøy _(176654)_: [@eisu24ab](https://www.github.com/eisu24ab), eisu24ab@student.cbs.dk

Paula Gattner _(176172)_: [@pa-ga](https://www.github.com/pa-ga), paga24ae@student.cbs.dk

______________________________________________________________________________________________

## Goodreads Reviews Data :books:
For our project, we explored reviews for 1,000 books on Goodreads. We aim to create a generated review trained on the reviews for each book. We also explore if extractive or abstractive summarization better generates coherent opinion-based summaries.

### Research Question:
_Can machine learning models effectively summarize multiple book reviews into a coherent, opinion-based summary?_

______________________________________________________________________________________________
### Data:
Download the raw scraped data from kaggle [here](https://www.kaggle.com/datasets/beridzeg45/book-reviews/data). 

Or use our instance [`Book Reviews.csv`](https://github.com/caoimhegall/CBS-NLP-Final/blob/main/data/Book%20Reviews.csv.zip).

______________________________________________________________________________________________
### Notebooks:
[`NGRAMS_NLP.ipynb`](https://github.com/caoimhegall/CBS-NLP-Final/blob/main/src/NGRAMS_NLP.ipynb): Summarization using NGrams. 

[`CLUSTERING_NLP.ipynb`](https://github.com/caoimhegall/CBS-NLP-Final/blob/main/src/CLUSTERING_NLP.ipynb): Summarization using KNN Clustering.

[`BART_NLP.ipynb`](https://github.com/caoimhegall/CBS-NLP-Final/blob/main/src/BART_NLP.ipynb): Summarization using BART Transformer.

[`PEGASUS_NLP.ipynb`](https://github.com/caoimhegall/CBS-NLP-Final/blob/main/src/PEGASUS_NLP.ipynb): Summarization using PEGASUS Transformer.

______________________________________________________________________________________________
### How to run: :pencil2:
1. Download the data [`Book Reviews.csv`](https://github.com/caoimhegall/CBS-NLP-Final/blob/main/data/Book%20Reviews.csv.zip)
2. Download the modeling Notebooks
3. Change the import to match your path for `Book Reviews.csv`

   ```df = pd.read_csv('\CHANGE TO YOUR PATH')```
5. Run in your IDE of choice

______________________________________________________________________________________________
