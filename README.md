# CS Fields & Subfields Data

This repository contains the dataset of 2,095 research articles published in the 2022 proceedings of the Association for Computing Machinery (ACM) conferences, which were analyzed in this paper:

Title: "Analysis of Research Trends in Computer Science: A Network Approach"

Authors: Ghazal Kalhor, Behnam Bahrak


If you use this dataset in your work, please cite our paper:

Kalhor, G. & Bahrak, B. Analysis of research trends in computer science: a network approach. *submitted to Applied Network Science* (2023).

# Datasets

We collected the following information for each paper:

* Title
* Fields
* Subfields
* Conference
* Track

## Conference Data Example

```python
import pandas as pd

df = pd.read_csv('ICMR22.csv')
df.head(3)
```

Conference| Track| Index| Paper|
|----|----|----|----|
|ICMR22| Reidentification| Information systems| Multiple Biological Granularities Network for Person Re-Identification|
|ICMR22| Reidentification| Information systems/Computing methodologies| TriReID: Towards Multi-Modal Person Re-Identification via Descriptive Fusion Model|
|ICMR22| Reidentification| Computing methodologies| Temporal-Consistent Visual Clue Attentive Network for Video-Based Person Re-Identification|

## Field Data Example

```python
import pandas as pd

df = pd.read_csv('Applied_computing.csv')
df.head(3)
```

Conference| Index| Paper|
|----|----|----|
|CHI22| Education| VocabEncounter: NMT-powered Vocabulary Learning by Presenting Computer-Generated Usages of Foreign Words into Users’ Daily Lives|
|CHI22| Law, social and behavioral sciences| User Perspectives and Ethical Experiences of Apps for Depression: A Qualitative Analysis of User Reviews|
|CHI22| Law, social and behavioral sciences| Human-AI Collaboration via Conditional Delegation: A Case Study of Content Moderation|
