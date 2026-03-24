# EdgePaper-Dataset

This repository provides the dataset and supplementary multimedia materials for our paper.

## Paper Information

Section:Experimental Evaluation

We evaluate CLDC on two complementary real-world datasets. The LastFM 1K dataset contains listening histories of 992 users. Each listening event is treated as a content request and used to model user interests for community detection. The Shanghai Telecom dataset provides over 7.2 million access records from 9,481 users and 3,233 base stations, capturing user mobility and BS deployment.

By combining the two datasets, we obtain traces that couple user preferences with movement. LastFM requests are aligned to Shanghai Telecom trajectories according to the user location at each time slot. We consider the top-500 items under a Zipf distribution. For each user, requests are split into 90% training data and 10% testing data.

Simulation and learning parameters are reported in the paper, and dataset visualizations are shown in Fig. 1.

## Repository Structure

```text
EdgePaper-Dataset/
├─ data/
├─ code/
├─ multimedia/
└─ README.md
