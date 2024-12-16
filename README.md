

## How to use this repo

1. Fork this repo
![Fork instructions](image.png)
2. Change parameters in `notebooks/conf/00_env_variables.ipynb`:
    - USER_ID - a number associated with your WUT email
    - TF_VAR_billing_account - billing account ID (GCP Console > Billing > Billing account ID)
3. Run the notebook `01_ds_lab_project_bootstrap.ipynb` on Colab by clicking the badge below
* Bootstrap GCP project [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/biodatageeks/ds-lab-infra/blob/master/notebooks/01_ds_lab_project_bootstrap.ipynb)
4. Run the notebook `02_ds_lab_infra_setup.ipynb` on Colab by clicking the badge
* Provision Big Data Lab resources [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/biodatageeks/ds-lab-infra/blob/master/notebooks/02_ds_lab_infra_setup.ipynb)
5. Go to GCP Console > Dataproc > Workbench > Open JupyterLab.
6. Authenticate to GitHub using:
```
gh auth login
```
7. Fork the repo `https://github.com/biodatageeks/ds-notebooks.git`
8. Clone the repo:
```
USER_NAME=myGitHubUsername
git clone https://github.com/$USER_NAME/ds-notebooks.git
```
9. Run the session_1 notebooks.