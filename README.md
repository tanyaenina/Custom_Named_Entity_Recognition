# Custom Named Entity Recognition for medical data in German

Named Entity Recognition (NER) is a Natural Language Processing task that identifies and classifies named entities in text into predefined categories such as people, organizations, locations, dates, and more. 

**The goal of this project is to automatically extract useful information from unstructured medical texts** by detecting entities such as _drugs, forms, dosages_, and others. 

I used the GERNERMED dataset, which consists of annotated German training data generated through automated translation from a public English dataset. This dataset was used for training the neural model GERNERMED, as described by Frei, J., & Kramer, F. (2022) in _GERNERMED: An open German medical NER model_, Software Impacts, 11, 100212.

To achieve the project's goal, I used the Python library spaCy to train and evaluate a custom NER model for German medical data from scratch.
