-- data --
Folder with the annotated datasets.
TSV files with two columns: sentence \t is_counterfactual.
is_counterfactual is a binary field: 
0 - is not counterfactual,
1 - is counterfactual.
Each dataset is split into train, validation, and test:
XX_train.tsv
XX_valid.tsv
XX_test.tsv
Where XX is EN, EN-ext, DE, JP as per naming in the paper.

-- clue words --
Folder contains lists of counterfactual clue words used for data collection.

-- annotation instructions -- 
Folder contains annotation instructions used by the annotators to manually label sentences as counterfactual or not.