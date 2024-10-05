# Wikipedia Analysis Project

## EDA
It is necessary to perform an EDA activity to statistically analyze and evaluate all the information content offered by Wikipedia. The bump you are provided with, has the following categories:

'culture',
'economics',
'energy',
'engineering',
'finance',
'humanities',
'medicine',
'pets',
'politics',
'research',
'science',
'sports',
'technology',
'trade',
'transport'

## Classification model
Once computed the EDA, the second part of the project consists on create a classification model in order to correctly classify documents, both given their contents and given their summary.
The classification is done through the Multinomian Naive Bayes algorithm.

## Dataset and environment
Dataset is available on https://proai-datasets.s3.eu-west-3.amazonaws.com/wikipedia.csv
We run the project into Databricks 15.4 LTS with Apache Spark 3.5.0 and Scala 2.12. The project has been developed to be run into a free Workspace.

## Dependencies
External libraries to be installed: com.johnsnowlabs.nlp:spark-nlp_2.12:5.4.1 (through Maven).
