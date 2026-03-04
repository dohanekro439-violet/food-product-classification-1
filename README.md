# 🍎 Classification des Produits Alimentaires

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-1.40.1-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

##  Description
Ce projet a pour objectif de **prédire si un produit alimentaire est bon ou mauvais pour la santé** à partir du dataset OpenFoodFacts.  
Le workflow inclut :  

- **Prétraitement des données** (nettoyage, sélection des features, normalisation)  
- **Entraînement d’un modèle de classification supervisée** (RandomForestClassifier)  
- **Évaluation des performances** du modèle  
- **Application Streamlit** pour tester de nouveaux produits et visualiser les résultats en temps réel  

### Objectifs du projet
- Permettre aux consommateurs de prendre des **décisions alimentaires plus éclairées**.  
- Enrichir les connaissances scientifiques sur les **effets à long terme de l’alimentation** sur la santé, l’environnement et la société.  
- Aider les producteurs alimentaires à **identifier et améliorer la qualité de leurs produits**.  
- Donner aux particuliers, chercheurs, associations, startups et entreprises les moyens de **résoudre rapidement les problèmes du système alimentaire à l’échelle mondiale**.  
- Guider les États dans l’**élaboration et la mise en œuvre de politiques de santé publique efficaces**.

##  Contenu du repository
- `Classification_Des_Produits_Alimentaires_Final.ipynb` : Notebook principal avec toutes les étapes (prétraitement, entraînement, évaluation).  
- `streamlit_app.py` : Application Streamlit pour tester le modèle sur de nouveaux produits.  
- `requirements.txt` : Dépendances Python exactes.  
- `images/` : Illustrations et logos utilisés dans le projet.  
- `model/` : Modèle entraîné et fichiers associés.  

##  Fichier `requirements.txt`
- `joblib==1.3.2`
- `numpy==1.24.4`
- `pandas==2.0.3`
- `Pillow==11.1.0`
- `scikit_learn==1.0.2`
- `streamlit==1.40.1`
