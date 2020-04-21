# covid-19 Open Research Dataset Challange Contextual Analysis With BERT

Clustering the contents of the data set provided by COVID-19 Open Research Dataset using Bidirectional Encoder Representations from Transformers (BERT).

The metadata.csv was used for the analysis. The file contains metadata for more than 28,000 documents. The file includes two important fields. These are abstract and titel fields. Help of these two fields of documents has been created an text body, which was embedded in a single vector space using BERT.

The solution of the problem is based on the idea that the elements of the embedded vector space formed from the text body of documents define the content of the text more precisely than the methods based on the document matrix. Therefore, clustering performed on such a body of text can more accurately show the content distribution of documents.

Furthermore plan was that, let each cluster is labeled with keywords.

Part of the solution is the source code written in python and all the outputs of the solver program as well.

Original:
https://www.kaggle.com/robertlakatos/covid-19-ordc-contextual-analysis-with-bert
