# analyse-de-donnees-medicales-
visualiseur de donnees medicales 
# 📊 Medical Data Visualizer

Ce projet analyse un ensemble de données médicales pour explorer la relation entre **les maladies cardiovasculaires** et des facteurs comme :

- les mesures corporelles (taille, poids, IMC),
- les résultats d'examens (cholestérol, glycémie, pression artérielle),
- et les habitudes de vie (tabagisme, alcool, activité physique).

Deux visualisations principales sont générées :
1. **Catplot** : comparaison des caractéristiques de santé entre patients atteints ou non de maladies cardiovasculaires.
2. **Heatmap** : matrice de corrélation des variables, basée sur des données nettoyées.

---

## 📁 Fichiers

- `medical_data_visualizer.py` : Contient le code de nettoyage, transformation et visualisation des données.
- `main.py` : Permet de lancer les fonctions et de sauvegarder les visualisations.
- `medical-examination.csv` : Fichier de données d'entrée.
- `test_module.py` : Fichier de tests unitaires.
- `catplot.png` : Résultat du graphique catégorique.
- `heatmap.png` : Résultat de la carte de chaleur.

---

## ▶️ Instructions

### 1. Installation des dépendances

```bash
pip install pandas seaborn matplotlib numpy
