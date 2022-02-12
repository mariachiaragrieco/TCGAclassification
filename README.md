# classification-project
Project in Python for Scientific Programming 2021 course (MSc in Bioinformatics for Computational Genomics) helded by Prof. Piro Rosario and Prof. Pinoli Pietro.

The notebook can be viewed here [nbviewer](https://nbviewer.org/github/mariachiaragrieco/classification-project/blob/main/SP_python_grieco.ipynb)

### Aim
The aim of this project is to analyze the TCGA GRCh38 Breast Cancer gene expression data taken from the [GenoSurf](http://geco.deib.polimi.it/genosurf/) interface using different machine learning techniques in order to classify normal and tumor samples.
In this light, different classification techniques of machine learning have been compared:
- Logistic Regression
- Support Vector Machines
- Linear Discriminant Analysis
- Random Forest
- DecisionTree
- K-Nearest Neighbors

### Outline
Firslty, data are dowloaded from the GenoSurf website using a concurrent programming strategy. Data manipulation is done with [pandas](https://pandas.pydata.org/).
For the classification task, a feature selection is performed before, then different algorithms are used and compared by different evaluation metrics.
Moreover, hyperparameters tuning and k-fold cross validation are carried out.

### Data
The [GenoSurf](http://geco.deib.polimi.it/genosurf/) interface is used to download the related data setting as options:
- project_name: ['tcga-brca']
- assembly: ['grch38']
- data_type: ['gene expression quantification']
- is_healthy:
    - ['false'] for tumoral data
    - [true] for normal data.






