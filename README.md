
# EDA Marketing & Segmentation Clients (RFM & K-Means)

Ce projet est dédié à l'analyse exploratoire des données (EDA) et à la segmentation stratégique d'une base de données clients dans le cadre d'une campagne marketing. L'objectif principal est d'identifier des segments de clientèle distincts afin d'optimiser les stratégies de ciblage et de fidélisation.

## 📌 Objectifs du Projet

*   **Exploration & Inspection :** Comprendre la structure du dataset, identifier les variables clés et analyser les comportements d'achat globaux.
*   **Nettoyage & Feature Engineering :** Traiter les valeurs manquantes, gérer les anomalies et préparer les données (transformation et mise à l'échelle) pour la modélisation.
*   **Analyse RFM :** Segmenter les clients de manière descriptive selon trois axes : Récence (Recency), Fréquence (Frequency), et Montant (Monetary).
*   **Modélisation Non Supervisée (K-Means) :** Appliquer l'algorithme K-Means pour découvrir des profils de clients complexes et valider la cohérence des clusters (Méthode du coude, Score de Silhouette).


## 📂 Structure du Notebook

Le projet est articulé autour du notebook principal `EDA.ipynb` structuré comme suit :

1.  **EXPLORATION DU DATASET (Inspection initiale) :** Chargement des données, analyse des types de variables et premières statistiques descriptives.
2.  **NETTOYAGE & FEATURE ENGINEERING :** Imputation des valeurs manquantes (ex: variable `Education`), détection des valeurs aberrantes, et normalisation (`StandardScaler`) des métriques RFM.
3.  **ANALYSE Recency Frequency Monetary (RFM) :** Calcul des scores RFM individuels et création d'une segmentation métier de référence.
4.  **VISUALISATION DE LA SEGMENTATION RFM :** Graphiques de distribution et analyses croisées des différents groupes de clients.
5.  **SEGMENTATION AVEC K-MEANS :** Entraînement de l'algorithme d'apprentissage non supervisé, sélection du nombre optimal de clusters ($K$) et interprétation business des profils générés.

---

## 🛠️ Stack

*   **Langage :** Python 3
*   **Environnement :** Jupyter Notebook / VS Code
*   **Manipulation de données :** `pandas`, `numpy`
*   **Visualisation graphique :** `matplotlib`, `seaborn`, `plotly`
*   **Machine Learning :** `scikit-learn` (`KMeans`, `StandardScaler`)

---

## ⚙️ Installation et Configuration

Pour exécuter ce notebook localement, suivez les étapes suivantes :

### 1. Cloner le dépôt
```bash
git clone [https://github.com/KevineNM/EDA_Marketing.git](https://github.com/KevineNM/EDA_Marketing.git)
cd EDA_Marketing