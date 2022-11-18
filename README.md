# Research-Project
`Thesis`: Automatic labelling of student results as PCD, MRNM, MBR and RET. 
In this research we are predicting student success of first and second year wits students using previous grades of the students.

# Data
The data is a synthetic data collected from wits university. We used `sklearn` or `Scikit-learn` which is a free software machine learning library for the Python programming language. The repo of sklearn can found [[here](https://github.com/scikit-learn/scikit-learn)]. The data was preprocessed in the notebook `DATA_PREPROCESSING` in the folder `Data Preprocessing`. The results achived are reproducible.

# Models
We used the following models:
- Naive Bayes (Becnchmark from the literature)
- Decision Trees (Becnchmark from the literature)
- Support Vector Machines (Becnchmark from the literature)
- Logistic Regression
- Random Forests
- Multi-Layer Perceptron
- Ensemble Meta-Based Trees, which is a Voting Classifier using Random Forests, Multi-Layer Perceptron and Decision Trees.

All the models did note get a great accuracy. NB, DT, SVM, LR, RF and MLP got an accuracy of less than 70%. EMT got an accuracy of above 70%. EMT was the best model for predicting student success of first and second year. NB was the worst model on both first and second year dataset. It achieved an accuracy of less than 60%. The results achieved are reproducible. So if you run the notebooks, you will get the same results which we achieved.

# Running
The models were run in [[google colab](https://colab.research.google.com/)] and files were saved in google drive. In order to run notebooks:
1. Create a folder in google drive called COMS HONS RESEARCH PROJECT.
2. Upload the notebook to colab and run them.

