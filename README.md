# ESE_corpus



This repository comprises a collection of Italian Named Entities extracted from Wikidata through SPARQL, along with the Python notebook used for the queries.
The corpus can be used to evaluate systems that aim to address the task of Entity Set Expansion (the semantic classes selected are the same of the [Wiki/APR](https://drive.google.com/drive/folders/0B4-hGx6CRafFdWxSZEY1MTN1OUk?resourcekey=0-QbulD2VuU6Nvc46rBnTYpw) benchmarks commonly used for this task). 

The script, though used to retrieve entities in Italian, is meant to be used with whatever language supported by Wikidata, provided that the correct label for the semantic class is passed as argument.
