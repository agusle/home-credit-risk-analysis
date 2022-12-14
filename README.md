<p align="center" width="100%">
    <img src="https://github.com/agusle/home-credit-risk-analysis/blob/main/img/project-logo.png" width = 400 height = 300>
</p>

<p align="center">
    <a href="https://github.com/agusle/home-credit-risk-analysis/commits/main">
    <img src="https://img.shields.io/github/last-commit/agusle/home-credit-risk-analysis?logo=Github"
         alt="GitHub last commit">
    <a href="https://github.com/agusle/home-credit-risk-analysis/issues">
    <img src="https://img.shields.io/github/issues-raw/agusle/home-credit-risk-analysis?logo=Github"
         alt="GitHub issues">
    <a href="https://github.com/agusle/home-credit-risk-analysis/pulls">
    <img src="https://img.shields.io/github/issues-pr-raw/agusle/home-credit-risk-analysis?logo=Github"
         alt="GitHub pull requests">
</p>

<p align="center">
  <a href="#-about">About</a> •
  <a href="#%EF%B8%8F-install-and-run">Install and Run</a> •
  <a href="#-contribute">Contribute</a> •
</p>

------------------

## 📖 About
- **Problem**: Binary classification with the aim of predicting risky credit operations.

The project consists in a complete pipeline to preprocess the data, train your model and then predict values for the [Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk/) Kaggle competition.

Kaggle is a web platform and community for data scientist and machine learning engineers where competitions and datasets are regularly published.

I want to predict whether the person applying for a home credit will be able to repay its debt or not. The competition finished many years ago, so you will find a lot of blog posts and code written for it.

The dataset is composed of multiple files with different information about loans taken. In this project I am going to exclusively work with the main files: *application_train.csv* and *application_test.csv*.

The competition uses [Area Under the ROC Curve](https://developers.google.com/machine-learning/crash-course/classification/roc-and-auc?hl=es_419) as the evaluation metric, so the models return the probabilities that a loan is not paid for each row.

- **Industries**: fintech, banks, insurtech, many others related. 

- **Solution**:
Predict whether a person applying for a home credit will be able to repay their debt or not. Data pre-processing for a large dataset of +350,000 transactions. Trained many supervised models achieving +0.72 ROC AUC. Models used where DecisionTree, XGBoost and LightGBM.

You can see the whole project in the following **notebook**: 
    - [Home credit default risk](https://github.com/agusle/home-credit-risk-analysis/blob/main/home-credit-default-risk.ipynb)

------------------

## ⚡️ Install and Run 

Listed below you'll find an example or application usage to run the project:

- **Open and execute in Google colab** (*you must be logged in with a google account*):
    - Open an internet browser and go to: https://colab.research.google.com/
    - On the menu select File / Open Notebook
    - Select the GitHub tab and copy the project url: https://github.com/agusle/home-credit-risk-analysis
    - Click on *home-credit-default-risk.ipynb*
    - Make a copy to your google drive acoount clicking the following icon ![copy-to-drive](https://github.com/agusle/home-credit-risk-analysis/blob/main/img/copy-to-drive.PNG)
    - Go to tab *Runtime* and select *Run all*.

 
- **Open and execute in Jupyter notebook:**
    - Open an internet browser and got to: https://nbviewer.org/
    - Insert project path: https://github.com/agusle/home-credit-risk-analysis and press Go! button.
    - Click on *home-credit-default-risk.ipynb* to see the notebook
    - If you want to execute it click on *execute on binder* icon ![binder](https://github.com/agusle/home-credit-risk-analysis/blob/main/img/binder.png)
    - Go to tab *Cell* and click on *Run all*.


- **Other ways** 
There are many other ways to open the notebook and run the whole project, you can see an example on the following link: https://soshnikov.com/education/how-to-execute-notebooks-from-github/

------------------

## 👍 Contribute
**Please follow these steps to get your work merged in.**

1. Add a [GitHub Star](https://github.com/agusle/home-credit-risk-analysis) to the project.
2. Clone repo and create a new branch: `$ git checkout https://github.com/agusle/home-credit-risk-analysis -b name_for_new_branch.`
3. Add a feature, fix a bug, or refactor some code :)
4. Write/update tests for the changes you made, if necessary.
5. Update `README.md`, if necessary.
4. Submit Pull Request with comprehensive description of changes
