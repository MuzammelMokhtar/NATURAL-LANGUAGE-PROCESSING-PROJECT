# NATURAL-LANGUAGE-PROCESSING-PROJECT
Welcome everyone :wave:this repo includes all the NLP codes.

This is just my side project whenever i'm free. This repository contains Jupyter notebooks.

## Installed Packages
These are the installed packages used for this project. All were installed in a conda environment (see below for how I created this).
```
python=3.11
nltk==3.9.1 
pandas==2.2.3 
matplotlib==3.10.0 
spacy==3.8.3 
textblob==0.18.0.post0 
vaderSentiment==3.3.2 
transformers==4.47.1 
scikit-learn==1.6.0 
gensim==4.3.3 
seaborn==0.13.2 
torch==2.5.1 
ipywidgets==8.1.5
```

## Conda Environment
Virtual environments are a great way to manage different packages for different projects. So, I just use it. :smile:

```
conda create --name nlp_course_env python=3.11
conda activate nlp_course_env
pip install nltk==3.9.1 pandas==2.2.3 matplotlib==3.10.0 spacy==3.8.3 textblob==0.18.0.post0 vaderSentiment==3.3.2 transformers==4.47.1 scikit-learn==1.6.0 gensim==4.3.3 seaborn==0.13.2 torch==2.5.1 ipywidgets==8.1.5
python -m spacy download en_core_web_sm
pip install ipykernel jupyterlab notebook
python -m ipykernel install --user --name=nlp_course_env
```
