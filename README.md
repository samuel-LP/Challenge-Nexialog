# Challenge Nexialog x MoSEF

## Description

L'objectif principal de ce challenge était de développer un modèle capable de prédire la probabilité de défaut selon 
les normes bâloises, en s'appuyant sur un ensemble diversifié de données, incluant des informations signalétiques, 
comportementales et financières relatives aux emprunteurs. 

## Structure du Projet

Le projet est structuré comme suit :

- `notebooks/` : Dossier contenant les Jupyter Notebooks pour l'analyse et la modélisation.
  - `Analyse_Préparation` : Dossier contenant les Notebooks sur l'analyse exploratoire et la préparation des données. 
  - `Modélisation_Interprétabilité` : Dossier contenant les Notebooks de modélisation, grille de score, segmentation et marge de conservatismes pour notre modèle le plus interprétable
  - `Modélisation_Performance` : Dossier contenant les Notebooks de modélisation, grille de score, segmentation et marge de conservatismes pour notre modèle le plus performant

- `script/` : 
  - `data_preparation` : module python contenant les classes de préparation des données.
  - `data_preparation` : module python contenant la classe permettant de créer la grille de score.


## Pour récupérer le projet

1. Cloner le repository

    ```bash
    git clone https://github.com/SamuelBaheux/Challenge_Nexialog.git
    ```

2. Créer un environnement virtuel

   2.1 Pour Windows : 
   
   ```bash
    python -m venv venv
    .\venv\Scripts\activate
   ```
   
   2.2  Pour Mac/Linux : 

   ```bash
    python3 -m venv venv
    source venv/bin/activate
   ```

3. Installer les dépendances : 
   ```bash
    pip install -r requirements.txt
   ```

## Authors

- [Jingyi Zhou](https://github.com/ZJY602)
- [Samuel Baheux](https://github.com/SamuelBaheux)
- [Samuel Launay Pariente](https://github.com/samuel-LP)
- [Axel Fritz](https://github.com/AxelFritz1)