# SALT (Sunbird African Language Technology) dataset

SALT is a multi-way parallel text corpus of English and five key Ugandan languages: Luganda, Lugbara, Acholi, Runyankole and Ateso. This dataset is designed to facilitate research and development in Machine Translation (both text and speech), Automatic Speech Recognition (ASR) and Text-to-Speech synthesis (TTS). It contains sentences in both text and audio format, with audio available in both crowdsourced and studio-quality speech (work in progress).

Each row in the dataset represents a sentence. This sentence is provided in six different languages (including English), with each language variant being presented in both text and audio format. Here's a breakdown of the row structure:

* **text**: This section contains the written form of the sentence in six languages. Each language is represented by a key-value pair, with the key being the language code and the value being the sentence in that language.

* **asr-speech**: This section contains links to the crowdsourced audio files for the sentence in six languages. Like in the text section, each language is represented by a key-value pair, where the key is the language code and the value is the filename of the audio file in that language.

* **tts-speech**: This section contains links to the high-quality studio-recorded audio files for the sentence. In the current version of the dataset, only Luganda and English are available in this format.

The dataset covers a wide range of locally relevant topics such as agriculture, health, and society, making it a versatile resource for developing and testing language technology applications for these languages. 

Each sentence in the dataset is available as an audio file that can be accessed by appending `https://salt-tts-data.s3.eu-west-1.amazonaws.com/` to the relative paths provided in the "asr-speech" column of the dataset. This allows for the practical usage of the dataset in various speech recognition tasks. Alternatively the zip files containing each language "asr-speech" column data can be obtained from 

This dataset is suited for those with a lower intermediate level of technical expertise, and can be used for a multitude of tasks including Machine Translation (text and speech), ASR, and TTS.

More details are in the following publication:

**Machine Translation For African Languages: Community Creation Of Datasets And Models In Uganda**. *Benjamin Akera, Jonathan Mukiibi, Lydia Sanyu Naggayi, Claire Babirye, Isaac Owomugisha, Solomon Nsumba, Joyce Nakatumba-Nabende, Engineer Bainomugisha, Ernest Mwebaze, John Quinn*. 3rd Workshop on African Natural Language Processing, 2022. \[[pdf](https://openreview.net/pdf?id=BK-z5qzEU-9)\]

This repository contains a notebook for training and evaluation which can be used to replicate the results in the paper. To try translation with the resulting models, see [translate.sunbird.ai](http://translate.sunbird.ai).

## Changelog

#### [v1.3] 2023-07-31
Added Multispeaker STT data for Acholi, Ateso, Luganda, Lugbara and Runyankole

#### [v1.2] 2023-04-21
Added TTS data for Luganda and English.

#### [v1.1] 2023-04-19
Data format changed, some duplicate sentences removed, and sentences partitioned into splits (train: 23,497; dev: 500, test: 500).

#### [v1.0] 2021-12-01
Initial commit of 25,000 sentences, with each sentence translated from English to Acholi, Ateso, Luganda, Lugbara and Runyankole.
