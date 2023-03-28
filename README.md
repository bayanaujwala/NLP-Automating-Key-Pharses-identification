# Automating Key Pharses identification for patient notes

#### Introduction 

* Clinical Skills examinations were recently added to the United States Medical Licensing Examination (USMLE), requiring test-takers to interact with patients and write case notes.
* Trained physicians later rated patient notes using rubrics that highlighted each case's main ideas (features). This procedure takes a significant amount of time and human resources.
* Natural language Processing and Deep Learning Algorithms can be used to improve the process.
* The dataset is from the NBME - Score Clinical Patient Notes Kaggle competition, and the goal of the competition is to speed up the evaluation process by finding feature contexts.
* We wanted to see the power of ‘BERT’ on this language comprehending task and compare different advancements.

Studied 4 different variations of BERT as follows:
* BERT-Base-Uncased 
* RoBERTa-Base 
* PubMedBERT (abstracts + full text)
* Bio Clinical BERT



#### Dataset

* patient_notes.csv - Approximately 40,000 Patient Note history sections.
* features.csv - The feature (or key idea) rubric for each clinical scenario.
* train.csv - Feature annotations for 1000 patient notes, a 100 for every ten instances.
After Data Preprocessing we can see the feature text, patient history, annotations and the location of the annotations.

Performance Evaluations:

* cross validation techniques, Confusion matrix and F1 score. 

Ablation study:

* Improvements with F-1 scores and model loss of BERT compared to a simple Neural Network base model.



