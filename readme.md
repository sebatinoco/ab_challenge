# AB InBev - Data Science Challenge

The project is structured as follows:

- /.: main folder, containing the scripts to run the project and other utility folders
- /demo/ab_challenge: folder with scripts and files related to web app
    - /data: data relevant to each stored model
    - /models: models to predict som and volume, stored in .json format 

The *requirements.txt* file contains all the necessary dependencies to run this project. The following libraries are highlighted:

- `pandas==2.0.2`
- `numpy==1.24.3`
- `matplotlib==3.7.1`
- `statsmodels==0.14.0`
- `scikit-learn==1.2.2`
- `prophet==1.1.4`
- `gradio==3.33.1`

In addition, the experiments were executed on `python==3.9`.

Running this project is straightforward, just follow these steps:

1. Install the necessary libraries: `pip install -r requirements.txt`
2. Replicate the results running `ab_challenge.ipynb` jupyter notebook.