# pynlp-conda-env

This is a standardized default package configuration for Natural Language Processing projects.\
I do not claim any rights to the below mentioned packages and do not provide a direct reupload.\
This repository only provides the necessary config files to recreate the setup.\
Repostitory will be updated regularly.

## Requirements
Please install the Anaconda Data Science Toolkit, available here: https://www.anaconda.com/products/individual \
(Technically you could also use it with a regular Python installation, however it is a good practice and quasi-standard.)

## Installation

To create a conda environment from the environment.yml file:\
`conda env create (-n <env_name>) -f environment.yml`

To create a conda environment from the requirements.txt file:\
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

Dependencies and some other useful smaller packages are included in the environment as well but are not specified here for the sake of brevity (and my sanity).\

## Additional steps
Here you can find useful commands to install some models / corpora that you will most likely need when working with text data.

- spacy English Core Model (S)\
  `python -m spacy download en_core_web_sm`
  
- spacy English Core Model (M)\
  `python -m spacy download en_core_web_md`

- NLTK downloader 
  ```
  python
  >>> import nltk
  >>> nltk.download()
  ```
  Select and download the preferred packages for your use case.

## FAQ & Troubleshooting

**How do I get rid of the gensim UserWarning about a certain package being unavailable?**
- Try suppressing these warnings with the python warning module or install the unavailable module.

  
