# DNABERT-Z

This repository contains code and data for the article ["Z-Flipon Variants reveal the many roles of Z-DNA and Z-RNA in health and disease"](https://www.biorxiv.org/content/10.1101/2023.01.12.523822v1.abstract)

The full genome predictions for human and mouse genomes can be downloaded [here](https://github.com/mitiau/Z-DNABERT/tree/main/beds)

To predict Z-DNA flipons on new data please use [this colab notebook](https://colab.research.google.com/github/mitiau/Z-DNABERT/blob/main/ZDNA-prediction.ipynb)

The finetuned DNABERT weights can be downloaded from google drive:
- [MM Kouzine data](https://drive.google.com/drive/folders/1JXJc9G6BQUIpvjATthv9Xyyp2uVRPz-h?usp=share_link)
- [MM Shin data](https://drive.google.com/drive/folders/1fvTX1MHq7Gn80SYa7ibqQEHMbvsT5cHl?usp=share_link)
- [HG Kouzine data](https://drive.google.com/drive/folders/1FbM8fDTWQ5hYLQVWv7F9okNE9DlXY7kY?usp=share_link)
- [HG Shin data](https://drive.google.com/drive/folders/1-3Ntyyjp-JfJ_V2ZXORedCDihAgckRQV?usp=share_link)

## Files in this repository

1_HG_chipseq.ipynb - Generate data splits for HG data with Chipseq labels. Train the models. Generate full genome predictions.

1_HG_kousine.ipynb - Generate data splits for HG data with Kouzine labels. Train the models. Generate full genome predictions.

1_MM_curax.ipynb - Generate data splits for MM data with Curax labels. Train the models.

1_MM_kousine.ipynb - Generate data splits for MM data with Kouzine labels. Train the models.

2_Generate_stats_hg_chipseq.ipynb - Calculate most frequently attended k-mers for HG data with Chipseq labels.

2_Generate_stats_hg_kouzine.ipynb - Calculate most frequently attended k-mers for HG data with Kouzine labels.

2_Generate_stats_mm_curax.ipynb - Generate full genome predictions for MM data with Curax labels. Calculate most frequently attended k-mers.

2_Generate_stats_mm_kouzine.ipynb - Generate full genome predictions for MM data with Kouzine labels. Calculate most frequently attended k-mers.

README.md - This file

ZDNA-prediction.ipynb - Standalone notebook for prediction of Z-DNA. Intended to be run in colab enviroment via: https://colab.research.google.com/github/mitiau/Z-DNABERT/blob/main/ZDNA-prediction.ipynb
