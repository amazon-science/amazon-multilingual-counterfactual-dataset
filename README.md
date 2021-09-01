## Amazon Multilingual Counterfactual Dataset (AMCD)

This repository contains a dataset described in the paper:

*I Wish I Would Have Loved This One, But I Didn’t – A Multilingual Dataset for Counterfactual Detection in Product Reviews.* James O’Neill, Polina Rozenshtein, Ryuichi Kiryo, Motoko Kubota, Danushka Bollegala. EMNLP'21. [arxiv version](https://arxiv.org/pdf/2104.06893.pdf)


The dataset contains *sentences* from Amazon customer reviews (sampled from [Amazon product review dataset](https://s3.amazonaws.com/amazon-reviews-pds/readme.html)) annotated for counterfactual detection (CFD) *binary classification*.
Counterfactual statements describe events that did not or cannot take place. Counterfactual statements may be identified as statements of the form – If p was true, then q would be true (i.e. assertions whose antecedent (p) and consequent (q) are known or assumed to be false).

The key features of this dataset are:

* The dataset is multilingual and contains sentences in English, German, and Japanese.
* The labeling was done by professional linguists and high quality was ensured.
* The dataset is supplemented with the annotation guidelines and definitions, which were worked out by professional linguists. As well as the clue word lists, which are typical for counterfactual sentences and were used for initial data filtering. The clue word lists were also compiled by professional linguists. 

 Please see paper for the data statistics, detailed description of data collection and annotation.


### Cite
If you use this dataset in your research, please cite the paper.


### License Summary

The documentation is made available under the Creative Commons Attribution-ShareAlike 4.0 International License. See the LICENSE file.
