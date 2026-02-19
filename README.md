markdown
# 🏠 Analyse du Marché Immobilier Français (DVF 2025)

## 📌 Présentation du Projet
Ce projet consiste en une analyse de bout en bout des transactions immobilières en France pour l'année 2025. L'objectif est de transformer les données brutes de l'État en une cartographie interactive permettant de visualiser les tensions de prix par zone géographique.

## 🛠️ Compétences Techniques
- **Langage :** Python 3.x
- **Librairies :** [Pandas](https://pandas.pydata.org) (Data Cleaning), [Folium](https://python-visualization.github.io) (Cartographie), [Numpy](https://numpy.org)
- **Données :** [DVF (Demandes de Valeurs Foncières)](https://www.data.gouv.fr) - Source officielle Etalab.
- **Géocodage :** Utilisation de l'[API Adresse](https://adresse.data.gouv.fr) pour la conversion des adresses en coordonnées GPS.

## 🚀 Étapes Réalisées
1. **Acquisition :** Récupération du dataset officiel DVF 2025.
2. **Nettoyage :** 
   - Filtrage des ventes (hors dépendances et adjudications).
   - Traitement des valeurs manquantes et aberrantes (Outliers).
   - Calcul du **prix au m²** par transaction.
3. **Visualisation :** Création d'une **Heatmap interactive** avec Folium pour identifier les zones les plus onéreuses.

## 📊 Résultats
La carte permet d'identifier visuellement les quartiers où la demande est la plus forte. 



<img width="1360" height="636" alt="image" src="https://github.com/user-attachments/assets/676c75e4-4e33-4790-8117-03f690cf1939" />


## 🔮 Prochaines Étapes
- [ ] Entraînement d'un modèle de régression pour prédire le prix d'un bien.
- [ ] Création d'un dashboard interactif avec [Streamlit](https://streamlit.io).
