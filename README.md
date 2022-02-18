# credit-risk-analysis
FinTech Challenge 12 - Credit Risk Analysis With Logistic Regression

---

## Analysis  
TBD


See full analysis details in the notebook [credit_risk_resampling.ipynb](app/credit_risk_resampling.ipynb)  


#### DataSet  

A single dataset was used to anlyze this space:
- [lending_data.csv](data/lending_data.csv) containing the following features about borrowers:  
    - contains data: `loan_size | interest_rate | borrower_income | debt_to_income | num_of_accounts | derogatory_marks | total_debt | loan_status`  


#### Assumptions
- Two logistic regression models will be analyzed, one predicting with original data, the second with resampled data.
- Resampled data will use the [RandomOverSampler](https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.RandomOverSampler.html) from the [imbalanced learn](https://imbalanced-learn.org/stable/index.html) module
- Both models will predict against the same test data.


## Summary

**Original Feature Model**  
TBD

**RandomOverSampler Model**  
TBD


**Visual Comparison Summary**  


Below are the `balanced_accuracy_score`, `confusion_matrix` and `classification_report` for each models performance.  

![Original Data](media/model_orig.png)  
![Resampled](media/model_resampled.png)  


See full analysis implementation, interactive charts, and maps in the notebook [credit_risk_resampling.ipynb](app/credit_risk_resampling.ipynb)  
---

## Technologies

This challenge uses [python](https://www.python.org/) 3.7 and the following [built-in](https://docs.python.org/3/py-modindex.html) modules:
- [os](https://docs.python.org/3/library/os.html#module-os)

Additionally, it requires:
- [matplotlib](https://matplotlib.org/)
- [pandas](https://pandas.pydata.org/)
- [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/)
- [scikit-learn](https://scikit-learn.org/stable/index.html)
- [imbalanced-learn](https://pypi.org/project/imbalanced-learn/)

See [installation](#installation) below for specifics.

---

## Installation

You will need Python 3.7, that supports for this application to run. An easy way to install python 3.7 is to download and install [Anaconda](https://www.anaconda.com/products/individual). After installing anaconda, open a terminal/command-prompt, and setup a python 3.7 environment, and then activate it like so:

```
# create an anaconda python 3.7 environment
# name can be any friendly name to refer to your environment, eg 'dev'
conda create --name dev python=3.7 anaconda

# activating the environment
conda activate dev

# use pip to install the above modules, eg:
pip install python-dotenv
...etc...
```


---

## Usage

The analysis is presented within a [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) notebook. To launch JupyterLab, from the root of this repo dirctory:

```
# within repo root 
$ jupyter lab
```
You can now open the notebook [credit_risk_resampling.ipynb](app/credit_risk_resampling.ipynb)  

---

## Contributors

[David Lopez](https://github.com/sububer)

---

## License

MIT