# ner-gliner-spacy

A simple example on NER using gliner-spacy. Please use python 3.12 or lower to avoid errors.

This project uses gliner-spacy and it is a zero-shot Named Entity Recognition (NER) model, with spaCy’s NLP capabilities.

### To install

```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

### May need to install the model
If it does not run successfully after pip install you can run this.
```
python -m spacy download en_core_web_sm
```