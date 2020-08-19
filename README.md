# Youtube-Comments---Intention-Mining
Mining Gamers' Intents on YouTube: A Study of Approaches to Classifying Intentions

Dataset directory contains the scrpit to extract the youtube comments for a specific video. In order to use this script, just copy the script and paste it in the script editor of a Google Sheet and run it.

Implementations directory contains :

  1. PreProcessing.ipynb - This file contains all the preprocessing steps to be used on the extracted youtube comments. In order to use the POS tagging you would require the     'taggerOutput.txt' file in the same directory.
  
  2. Lexical Analysis of Datset.ipynb - This contains the steps to calculate the lexical rechiness of the dataset.
  
  3. TF-IDF.ipynb - This file contains the intention mining implementation using the TF-IDF vectors as the input feature for the machine learning models.
  
  4. BoW.ipynb - This file contains the intention mining implementation using the Word Count vectors as the input feature for the machine learning models.
