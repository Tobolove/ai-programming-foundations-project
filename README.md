# AI Programming Foundations Project: Titanic Data Workflow

This project is a reproducible data pipeline and workflow in a notebook that loads, cleans, explores and visualizes passenger data from the Titanic tragidy. 

It uses the training dataset of the Kaggle dataset [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data) and checks how survival differed by sex, passenger class and age. The cleaned data and the reusable cleaning and analysis functions can be taken as the foundation for a later machine learning model that predicts survival rates for the kaggle competion.

## Files in this project

- data_workflow.ipynb: the notebook with the complete pipeline and the workflow
- train.csv: the dataset from Kaggle
- requirements.txt the packages (Python) created by pip freeze > requirements.txt

## How to run this!

1. clone the repo
```bash
   git clone https://github.com/Tobolove/ai-programming-foundations-project.git
   cd ai-programming-foundations-project
   ```

2. create and then activate the virtual environment
```bash
   python -m venv .venv
   .venv\Scripts\activate
   ```

3. Install all of the necessary libraries and packages (dependencies):
```bash
   pip install -r requirements.txt
   ```

4. Open and run the notebook
```bash
   jupyter notebook data_workflow.ipynb
   ```

5. Run and enjoy all the Cells :)
Run → Run All Cells. train.csv is already in the repository, so no download is needed.