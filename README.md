# SALT (Sunbird AI Language Translation) dataset
SALT is a multi-way parallel text corpus of Engish and five key Ugandan languages: Luganda, Lugbara, Acholi, Runyankole and Ateso. The dataset contains 25,000 sentences covering a range of topics of local relevance, such as agriculture, health and society. Each sentence is translated into all six languages.

More details are in the following publication:

**Machine Translation For African Languages: Community Creation Of Datasets And Models In Uganda**. *Benjamin Akera, Jonathan Mukiibi, Lydia Sanyu Naggayi, Claire Babirye, Isaac Owomugisha, Solomon Nsumba, Joyce Nakatumba-Nabende, Engineer Bainomugisha, Ernest Mwebaze, John Quinn*. 3rd Workshop on African Natural Language Processing, 2022. \[[pdf](https://openreview.net/pdf?id=BK-z5qzEU-9)\]

This repository contains a notebook for training and evaluation which can be used to replicate the results in the paper. To try translation with the resulting models, see [translate.sunbird.ai](http://translate.sunbird.ai).


## Text-to-speech data
This repo also contains text-to-speech data for English and Luganda in the `tts-data` folder. There are 2 csv files:
- `english_studio_tts_dataset.csv`
- `luganda_studio_tts_dataset.csv`

##### Column description
- The column `salt_sentence_id` refers to the id of the sentence in the SALT translation dataset.
- The column `sentence` contains corresponding sentences.
- The column `audio_file` points to the name of the audio file.

The audio files can be downloaded as a zip file from here: https://salt-tts-data.s3.eu-west-1.amazonaws.com/tts-data.zip.
