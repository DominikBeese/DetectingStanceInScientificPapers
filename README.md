[![](https://img.shields.io/badge/Python-3.10.6-informational)](https://www.python.org/)
[![](https://img.shields.io/github/license/DominikBeese/DetectingStanceInScientificPapers?label=License)](/LICENSE)
# Detecting Stance in Scientific Papers
Data and code for the paper ["Detecting Stance in Scientific Papers: Did we get more Negative Recently?"](https://arxiv.org/abs/2202.13610) by Dominik Beese, Begüm Altunbaş, Görkem Güzeler, and Steffen Eger, 2022.

<img src="https://user-images.githubusercontent.com/111588769/186473960-ff7a9f1a-016f-456b-9364-b64825733cd1.png" alt="Average Stance per Year and Domain" width="410px">


## Content
The repository contains the following elements:
 * 📂 [Data](/Data)
   * 📂 [Datasets](/Data/Datasets) of paper titles and abstracts
   * 📂 [Human Annotated Data](/Data/Human%20Annotated%20Data) regarding stance of a paper
   * 📂 [Model Predicted Data](/Data/Model%20Predicted%20Data) with predictions of our model for all [Datasets](/Data/Datasets)
 * 📂 [Model](/Model) used for the analysis
 * 📂 [Code](/Code) to train and apply models
 * 📂 [Analysis](/Analysis) code to generate the plots


## Citation
```
@article{DetectingStanceInScientificPapers,
          title = "Detecting Stance in Scientific Papers: Did we get more Negative Recently?",
         author = "Dominik Beese and Beg{\"u}m Altunba{\c{s}} and G{\"o}rkem G{\"u}zeler and Steffen Eger",
           year = "2022",
         eprint = "2202.13610",
  archivePrefix = "arXiv",
   primaryClass = "cs.CL".
}
```
> **Abstract:** In this paper, we classify scientific articles in the domain of natural language processing (NLP) and machine learning (ML) into whether (i) they extend the current state-of-the-art by introduction of novel techniques which beat existing models or whether (ii) they mainly criticize the existing state-of-the-art, i.e., that it is deficient with respect to some property (e.g., wrong evaluation, wrong datasets, misleading task specification). We refer to contributions under (i) as having a "positive stance" and contributions under (ii) as having a "negative stance" (to related work). We annotate over 1.5k papers from NLP and ML to train a SciBERT based model to automatically predict the stance of a paper based on its title and abstract. We then analyze large-scale trends on over 41k papers from the last ~35 years in NLP and ML, finding that papers have gotten substantially more positive over time, but negative papers also got more negative and we observe considerably more negative papers in recent years. Negative papers are also more influential in terms of citations they receive.
