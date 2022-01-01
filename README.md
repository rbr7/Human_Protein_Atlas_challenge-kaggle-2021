# Human_Protein_Atlas_challenge-kaggle-2021
kaggle

## Problem Statement

Study of a single cell enables the discovery of mechanisms that are difficult to observe with multi-cellular research. This is a weakly supervised multi-label classification problem and a code competition. Solving single-cell image classification challenge will help to characterize single-cell heterogeneity in the dataset
provided, by generating more accurate annotations of the subcellular localizations for thousands of human proteins in individual cells. This may accelerate the growing understanding of how human cells function and how diseases develop, both of which are critical to the research community.

## DATA

The Human Protein Atlas is an initiative based in Sweden aimed at mapping proteins in all human cells, tissues, and organs. The data in the ​ Human Protein Atlas database​ is freely accessible.​ :

1) The data page on Kaggle provides a set of full size original images (a mix of 1728x1728, 2048x2048 and 3072x3072 PNG files) in train.zip and test.zip​ .
2) The image level labels from train.csv and the filenames for the test set from sample_submission.csv.
3) Public HPA images available to download in ​ the notebook​ .
4) The 16-bit version of the training images are available ​ here​ .
5) Each sample consists of four files, with every file representing a different filter on the subcellular protein patterns represented by the sample. The format is [filename]_[filter color].png for the PNG files. Colors are red for microtubule channels, blue for nuclei channels,yellow for Endoplasmic Reticulum (ER) channels, and green for protein of interest, as mentioned.
