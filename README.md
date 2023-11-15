# WineClassificationAnalysis

## Table of contents
* [Description](#description)
* [Key Features](#keyfeatures)
* [Objectives](#objectives)
* [Technologies](#technologies)
* [Setup](#setup)
* [Authors](#authors)
* [Licence](#licence)

## Description
This GitHub repository houses a Python-based project that aims to provide an in-depth analysis of wine flavors and quality assessments. By leveraging natural language processing (NLP) a sentiment analysis techniques, this project seeks to interpret and score wine tasting descriptions, helping enthusiasts and experts better understand and appreciate the nuances of wine.

## Key Features
* Data Collection: We gather a comprehensive dataset of wine tasting notes, including descriptions of flavors, aromas, and other sensory characteristics.

* Preprocessing: Text data is preprocessed to ensure consistency and prepare it for sentiment analysis.

* Sentiment Analysis: State-of-the-art sentiment analysis models are employed to gauge the sentiment expressed in tasting descriptions, helping us understand the emotional undertones.

* Classification: Wine descriptions are classified into various taste categories (e.g., fruity, oaky, earthy) based on sentiment analysis results.

* Cata Score Generation: A unique scoring system is developed to assign quantitative ratings to wine descriptions, aiding in wine evaluation and recommendation.

## Objectives
### General
* To develop a comprehensive wine taste analysis system using Python, which leverages advanced natural language processing (NLP) techniques and sentiment analysis to interpret wine tasting descriptions
* Categorize them into taste profiles, and generate quantitative cata scores, ultimately enhancing the understanding and appreciation of wine.

### Specific
* To create a process that uses Natural Language Processing
* Organize the given data

## Technologies
This project is created with:
* python: 3.8.10

## Setup
To run this project you need to have python installed and clone this repository:
```
$ sudo apt install python3 python3-pip
$ git clone https://github.com/miguelgonrod/WineClassificationAnalisis.git
$ cd WineClassificationAnalisis
```

Now you need to install the requirements. Ensure to install the spaCy model as well.
```
$ pip install -r requirements.txt
python -m spacy download en_core_web_md
```

Still in progress....

## Authors
More details about the authors in the [AUTHORS.md](https://github.com/miguelgonrod/WineClassificationAnalisis/blob/main/AUTHORS.md) file.
Additionally, to clarify, the dataset is not ours, to look up for the original creator refer to the original dataset: https://www.kaggle.com/datasets/zynicide/wine-reviews

## License
WineClassificationAnalysis is available under the BSD-3-Clause license. See the LICENSE file for more details.
