# Neuefische Data Science boot camp
---
## EDA project 
![built](https://img.shields.io/appveyor/build/ChristianKlingler/EDA_project) [![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try) 


[Neuefische GmbH](https://www.neuefische.de/) provides for a variety of boot camps as advanced training courses. Amongst the training courses are a data science course. Integral part of this training are hands-on excercises, like this one here. 

This repository contains the outcome of an exploratory data analysis (EDA) focussing on applying techniques concerning EDA workflow, Python coding, basic statistical analysis, and data presentation. 

---
## Data and tasks

The underlying dataset of this EDA contains market information about home sales in King County (USA). Details of the dataset can be found in the [column_names](column_names.md) file. Task of the EDA project are described in the [assignment](assignment.md) file. 

### Aim
The aim of the EDA exercise:
- choose a stakeholder (either seller or buyer, different individuals with unique demands)
- find at least **3 insights** about the overall data (incl. geographical analysis)
- generate at least **3 recommendations** for stakeholder
- upload the outcome on a **github repository**
- present and discuss outcome in a **10min presentation** at the course meetings

### Results
The results of the EDA are described in the [EDA](EDA.ipynb) jupyter notebook file. The full EDA contained the following features:
* Choice of stakeholder and demands on the outcome
* Description of underlying data
* Data cleaning process
* Descriptive statistics
* Hypothesis generation
* Generation of task
* Process of developing recommendations for stakeholder
* Conclusion
* Outlook

---
### Requirements for running code

- pyenv
- python==3.9.4

### Setup

For this purpose you use following commands:

```bash
pip install -r requirements.txt
```

#### Unit testing

If you write python scripts for your data processing methods, you can also write unit tests. In order to run the tests execute in terminal:

```bash
pytest
```

This command will execute all the functions in your project that start with the word **test**.
