# Prudential Life Insurance Assessment Prediction from Kaggle

The basic aim of this competition is to accurately classify risk and predict the Response variable for each ID in the test set. 
The Response variable is a measure that has 8 levels of risk.

## Dataset Features

* Id A unique identifier associated with an application.

* Product_Info_1-7 A set of normalized variables relating to the product applied for

* Ins_Age Normalized age of applicant

* Ht Normalized height of applicant

* Wt Normalized weight of applicant

* BMI Normalized BMI of applicant

* Employment_Info_1-6 A set of normalized variables relating to the employment history of the applicant.

* InsuredInfo_1-6 A set of normalized variables providing information about the applicant.

* Insurance_History_1-9 A set of normalized variables relating to the insurance history of the applicant.

* Family_Hist_1-5 A set of normalized variables relating to the family history of the applicant.

* Medical_History_1-41 A set of normalized variables relating to the medical history of the applicant.

* Medical_Keyword_1-48 A set of dummy variables relating to the presence of/absence of a medical keyword being associated with the application.

* Response This is the target variable, an ordinal variable relating to the final decision associated with an application

## Installation (Optional if you already have libraries installed)

Create a Virtual Environment
```bash
pip install virtualenv
python<version> -m venv <virtual-environment-name>
<virtual-environment-name>\Scripts\activate

```
Install the requirements.txt

```bash
pip install -r /requirements.txt
```
(Optional) If you want to run the .ipynb file on Jupyter Notebook, run the following command in it first to access the Virtual Environment:

```
ipython kernel install --user --name=<virtual-environment-name>
```

After this, just run the notebook file. 

Feel free to reach out if you have any issues.
