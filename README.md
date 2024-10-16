# Description
This README will be used to run the project1.py 

The program take in 3 arguments:

Argument 1: Your topics.json file that will contain all of the queries you will be getting results for (Format: ID, Title, Body, Tags)
Argument 2: Your Answers.json file containing all of the relevant answers to your queries
Argument 3: The filepath on your computer where you want the index path to be. This should most likely be in the same folder that you are running this program, along with your Answers.json and topics.json

Example: project1.py Answers.json topics_1.json 'C:/Users/Personal/Desktop/Ubuntu/index1'

While having to put an input argument for where you want to index is quite annoying, it was the approach I took to make this code modular and able to be used wherever it needs to be.


# Results

After you are done running your program, you will be returned 2 different .tsv files. 
  - res1_TF_IDF.tsv will be your results for the TF-IDF system
  - res1_BM25.tsv will be your results for the BM25 system

These results can be used in either TREC_Eval or Ranx. I personally used Ranx for evaluating the results for my project.
