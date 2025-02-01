# Car Price Data Mining

## Introduction
Ce projet analyse un dataset de prix de voitures pour identifier les tendances et les facteurs influençant les prix. L'objectif est d'explorer les données et d'appliquer des modèles de machine learning pour prédire le prix des voitures.


## Structure du Projet
Voici l'arborescence des fichiers du projet :

```
├── data
│   ├── car_price_dataset.csv
├── notebooks
│   ├── car_price_dataset.ipynb
├── reports
│   ├── rapport.pdf
├── README.md

```

## Contenu du Dataset
Le dataset contient les informations suivantes :
- `Brand` : Marque de la voiture
- `Model` : Modèle de la voiture
- `Year` : Année de fabrication
- `Engine_Size` : Taille du moteur
- `Fuel_Type` : Type de carburant
- `Transmission` : Type de transmission
- `Mileage` : Kilométrage parcouru
- `Doors` : Nombre de portes
- `Owner_Count` : Nombre de propriétaires précédents
- `Price` : Prix de la voiture

## Analyses Exploratoires
1. **Distribution des prix des voitures** : Histogramme des prix.
2. **Relation entre prix et année de fabrication** : Visualisation par nuage de points.
3. **Distribution du kilométrage** : Histogramme.

## Préparation et Modélisation
1. **Nettoyage des données** : Gestion des valeurs manquantes et conversion des types de données.
2. **Feature Engineering** : Création de nouvelles variables pour améliorer la prédiction.
3. **Modèles Utilisés** : 
   - Régression linéaire
   - Random Forest
   - XGBoost

## Exécution du Projet
### Prérequis
Installez les bibliothèques requises :
```bash
!pip install -q pandas sckit-learn
```

### Exécution
1. Lancez le notebook `notebooks/car_price_dataset.ipynb`
2. Consultez le rapport d'analyse `reports/rapport.pdf`

## Résultats et Interprétations
Les analyses effectuées montrent des tendances claires dans les prix des voitures en fonction de divers facteurs. Les modèles de machine learning prédisent efficacement les prix avec une précision de plus de 85%.

