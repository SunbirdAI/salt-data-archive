# SALT (Sunbird African Language Technology) dataset
SALT is a multi-way parallel text corpus of Engish and five key Ugandan languages: Luganda, Lugbara, Acholi, Runyankole and Ateso. The dataset contains 25,000 sentences covering a range of topics of local relevance, such as agriculture, health and society. Each sentence is translated into all six languages.

More details are in the following publication:

**Machine Translation For African Languages: Community Creation Of Datasets And Models In Uganda**. *Benjamin Akera, Jonathan Mukiibi, Lydia Sanyu Naggayi, Claire Babirye, Isaac Owomugisha, Solomon Nsumba, Joyce Nakatumba-Nabende, Engineer Bainomugisha, Ernest Mwebaze, John Quinn*. 3rd Workshop on African Natural Language Processing, 2022. \[[pdf](https://openreview.net/pdf?id=BK-z5qzEU-9)\]

This repository contains a notebook for training and evaluation which can be used to replicate the results in the paper. To try translation with the resulting models, see [translate.sunbird.ai](http://translate.sunbird.ai).

## Changelog

#### [v1.2] 2023-04-21
Added TTS data for Luganda and English.

#### [v1.1] 2023-04-19

Data format changed, some duplicate sentences removed, and sentences partitioned into splits (train: 23,497; dev: 500, test: 500).

#### [v1.0] 2021-12-01

Initial commit of 25,000 sentences, with each sentence translated from English to Acholi, Ateso, Luganda, Lugbara and Runyankole.
