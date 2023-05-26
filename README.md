# Repo for Implicit References Dataset from the paper Resolving Implicit References in Instructional Text

This repository contains the dataset from the paper 'Resolving Implicit References in Instructional Text'. The dataset contains 
6,014 sentences with implicit references occuring in WikiHow Instructions, created from the WikiHowToImprove dataset. 

The current version of the data contains the following columns: 
- ArticleName: the name of the WikiHow Article. 
- RevisedSentence: the original sentence + explicit reference (in other words: the revised sentence). 
- Reference: the reference 
- Context: the sentences preceding the original sentence + explicit reference. 

# Citation 

Please cite the following paper when the data is used: 

``` 
@inproceedings{anthonio-roth-2021-resolving,
    title = "Resolving Implicit References in Instructional Texts",
    author = "Anthonio, Talita  and
      Roth, Michael",
    booktitle = "Proceedings of the 2nd Workshop on Computational Approaches to Discourse",
    month = nov,
    year = "2021",
    address = "Punta Cana, Dominican Republic and Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.codi-main.6",
    doi = "10.18653/v1/2021.codi-main.6",
    pages = "58--71",
```

# Contact 
If you have any questions about this dataset, please contact Talita Anthonio via e-mail: talita.anthonio@yahoo.com. 

# Related datasets: 
- WikiHowToImprove: https://github.com/irshadbhat/wikiHowToImprove (paper: https://aclanthology.org/2020.lrec-1.702/)
- CLAIRE or SemEval-2021 Task 10 dataset: https://github.com/acidAnn/claire (paper: https://aclanthology.org/2022.lrec-1.354/) 
