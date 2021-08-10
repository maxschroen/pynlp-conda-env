# pynlp-conda-env

This is a standardized default package configuration for Natural Language Processing projects.\
I do not claim any rights to the below mentioned packages and do not provide a direct reupload.\
This repository only provides the necessary config files to recreate the detailed setup.\
Repostitory will be updated regularly.

## Installation

To create a conda env from the environment.yml file:\
`conda env create (-n <env_name>) -f environment.yml`

To create a conda env from the requirements.txt file:\
`conda create -n <env_name> -f requirements.txt`

Verify installation with:\
`conda env list`

## Included Main Packages
- numpy
- pandas
- scipy
- tqdm
- jupyter
- sklearn
- nltk
- gensim
- textblob
- spacy
- matplotlib
- seaborn

Dependencies and some useful smaller packages are included in the environment.

