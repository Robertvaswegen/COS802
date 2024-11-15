# COS802
This is a repo for my work in COS802

For my COS 802 project, I made use of different Natural Language Processing (NLP) techniques. The project is relatively a plug a play. Due to the computing need. The files were saved in parquet files and then used later on in visualization, due to this, there might be packages that would need to be installed within a specific line of code.

The script is order in the following way to achieve the NLP extraction.

The script is organized into the following sections:

1) Package Installation and Data Preprocessing

-Installing necessary libraries.
-Cleaning and preprocessing the data.

2) BERTopic Setup and Visualization

-Topic modeling with BERTopic.
-Visualizing topics using interactive charts.

3) LDA Setup and Visualization

-Traditional Latent Dirichlet Allocation (LDA) modeling.
-Visualization of LDA results using pyLDAvis.

4) RoBERTa for Sentiment Analysis

-Sentiment analysis pipeline using the RoBERTa model.
-Visualization of sentiment trends.

5)NER Model and Visualization

-Named Entity Recognition (NER) using spaCy.
-Geospatial visualization of extracted locations on a map.


### NOTE

My script crashed on code cell 8, please just continue the process. The script can still continue after the crash, just run the process futher.

###


#Data
The data was obtained through the University of Pretoria, from the Computer science Depratment.
The data is thus not in the public domain. However, one can create your own data. 

The data used was from the SAPS X (Twitter) page, which dated from the ~25th of March 2021 to ~15 of June 2023. The data contained 47 unique languages, but this project only focused on English tweets.
 
