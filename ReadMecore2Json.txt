Title:-
Converting Outputs of NLP models to JSON format.

Introduction:-
In this section of code our aim was to store the classified data using pretrained NLP models in JSON format. The text file was scrapped from the Canadian 
leagal court documents. We classified the data using the pretrained NLP models. Appropriate data transformation was done on the data and fed to NLP 
pretrained models like BERT, BOW, and FastText. Outputs of each model was stored in JSON file.

Steps Performed:-
1. Load appropriate libraries.
2. Read the text file.
3. Split the data on paragraphs.
4. Convert the data to lowercase, strip it and remove punctuations from it.
5. Load pretrained BOW models and predict the classification labels.
6. Store the results in a JSON file.
7. Load pretrained Fasttext models and predict the classification labels.
8. Store the results in a JSON file.
9. Load pretrained BERT models and predict the classification labels.
10. Store the results in a JSON file.

Libraries:-
nltk, pcikle, numpy, json, fasttext, tranformers, re, and string.

Language:-
Python.