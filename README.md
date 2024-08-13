# Named Entity Recognition (NER) Task
## Overview
### This project focuses on implementing a Named Entity Recognition (NER) model using the bert-base-cased model. 

### The task is to classify words in text into nine categories based on entity types and position:
*   Entity Types: LOC (Location), MISC (Miscellaneous), ORG (Organization), PER (Person).
*   Position Types: B (Beginning), I (Inside), O (Outside/Not an entity).

### The model is trained on the CoNLL-2003 dataset (conll003) and achieves an accuracy of 99.5% on the test, training, and validation sets.

## NER Tags
### The NER task involves classifying each word into one of the following categories:

*  O: The word doesn’t correspond to any entity.
*  B-PER/I-PER: The word corresponds to the beginning of or is inside a person entity.
*  B-ORG/I-ORG: The word corresponds to the beginning of or is inside an organization entity.
*  B-LOC/I-LOC: The word corresponds to the beginning of or is inside a location entity.
*  B-MISC/I-MISC: The word corresponds to the beginning of or is inside a miscellaneous entity.

## Features
*  BERT Model: Implements the bert-base-cased model for NER.
*  High Accuracy: Achieves 99.5% accuracy on the CoNLL-2003 dataset.
*  Comprehensive Preprocessing: Extensive text preprocessing to ensure optimal model performance.
