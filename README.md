# Challenge Nexialog x MoSEF

## Description

The goal of this challenge was to develop a model capable of predicting the likelihood of default according
to Basel standards, using a diverse set of data, including demographic, behavioral, and financial information about borrowers.

The presentation of these results was made through a dashboard developed with Plotly Dash.

## Project structure

The project is structured as follows:

- `notebooks/` : Folder containing the Jupyter notebooks for the EDA and the modelisation.
  - `Analyse_Préparation` : Folder containing the Jupyter notebooks for the EDA and the data preparation.
  - `Modélisation_Interprétabilité` : Folder containing the modeling Notebooks, scoring grid, segmentation, and conservatism margins for our most interpretable model.
  - `Modélisation_Performance` : Folder containing the modeling Notebooks, score grid, segmentation, and conservatism margin for our most efficient model.
  - `XGBoost` : Folder containing the modeling Notebooks, score grid, and segmentation with a Boosting model.
    
- `script/` : Folder containing the python scripts.
  - `data_preparation` : Python module containing data preparation classes.
  - `Logit_utils` : Python module containing the class for creating the score grid for the Logit model.
  - `XGB_utils` : Python module containing classes for training an XGBoost model and creating the scoring grid.

- `app/` : Folder containing the scripts for the application.
  - `app_utils` : Python module containing functions useful to the application.
  - `builders` : Python module containing the HTML code of the dashboard.
  - `callbacks` : Python module containing functions for interacting with the dashboard.
  - `plot_analyse` : Python module containing the graphs for the data analysis section.
  - `plot_utils` : Python module containing some graphics
  - `vars` : Python module containing the variables

## To retrieve the project

1. Clone the repository

    ```bash
    git clone https://github.com/Samuel-LP/Challenge_Nexialog.git
    ```

2. Create a virtual environment

   2.1 On Windows : 
   
   ```bash
    python -m venv venv
    .\venv\Scripts\activate
   ```
   
   2.2  On Mac/Linux : 

   ```bash
    python3 -m venv venv
    source venv/bin/activate
   ```

3. Install the dependancies : 
   ```bash
    pip install -r requirements.txt
   ```

## To launch the application

First, position yourself at the root of the project:
```bash
cd Challenge-Nexialog
```

Then, enter the following command:

```bash
python app.py
```

All you'll have to do is click on the link in the terminal to use our application, Nexiamod!

## Authors

- [Jingyi Zhou](https://github.com/ZJY602)
- [Samuel Baheux](https://github.com/SamuelBaheux)
- [Samuel Pariente Launay](https://github.com/samuel-LP)
- [Axel Fritz](https://github.com/AxelFritz1)
