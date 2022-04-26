# Contributing to `SALT`

Welcome, and thank you for considering contributing to the `SALT` dataset.

## Overview
`SALT` is a multi-way parallel text corpus of 5 key Ugandan languages.

### Dataset format
The dataset comprises of a file in this repository named [sunbird-ug-lang-v1.0.jsonl](sunbird-ug-lang-v1.0.jsonl).

This file is in the `.jsonl` (JSON Lines) format.

Each object contains an `English` sentence and all its corresponding translations in the 5 Ugandan local languages of `Luganda`, `Runyankole`, `Ateso`, `Lugbara` and `Acholi`. 

#### An example:

```{"English":"The community should be sensitised on hygiene and sanitation-related issues.","Luganda":"Abantu balina okutegezebwa ku nsonga ezeekuusa ku buyonjo.","Runyankole":"Abantu bashemereire kusomesibwa ahaby'obuyonjo n'ebihorooni.","Ateso":"Ekot itunga isisianakinete nuka aidar aila.","Lugbara":"Le Ongulumu eyi ma esu imbata e'yo alata ni 'diyi ma dria ra.","Acholi":"Dano ma ikabedo man omyero gunong pwony ikit me gwoko lengo"}```

## How to contribute

Contributions are done by adding extending the exisiting dataset file or adding a new one, in the same format as described above.

In general, we follow the `fork-and-pull` Git workflow:
1. Fork the repository to your own Github account
2. Clone the project to your machine
3. Create a branch locally with a succinct but descriptive name
4. Commit changes to the branch, following proper formatting guidelines
6. Push changes to your fork
7. Open a PR in our repository (refer to our [PR template](.github/PULL_REQUEST_TEMPLATE.md))
8. We will review the PR and add the new datasets if it meets the requirements
